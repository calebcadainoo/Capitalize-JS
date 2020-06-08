# Capitalize-JS
Capitalize First Character of Each Word in string JS

```sh
// CAPTALIZE FIRST LETTER OF WORDS IN STRING
function capitalize(str) {
    str = str.split(" ");

    for (var i = 0, x = str.length; i < x; i++) {
        str[i] = str[i][0].toUpperCase() + str[i].substr(1);
    }

    return str.join(" ");
}
```
