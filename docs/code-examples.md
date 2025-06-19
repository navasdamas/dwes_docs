An example of a code block for Python:

```js title="increaseCounter.js" linenums="1"
let count = 0;

function increaseCounter() {
    count++;
    document.getElementById("counter").textContent = count;
}
```

> Nota: se puede cambiar la numeración para que en lugar de empezar en 1 empiece con otro número de línea.

```js title="code-examples.md" linenums="1" hl_lines="2-4"
// Function to concatenate two strings
function concatenateStrings(str1, str2) {
  return str1 + str2;
}

// Example usage
const result = concatenateStrings("Hello, ", "World!");
console.log("The concatenated string is:", result);
```