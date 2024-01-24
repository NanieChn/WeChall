Training: ASCII
--
```javascript
const code = "76, 97, 32, 115, 111, 108, 117, 116, 105, 111, 110, 32, 101, 115, 116, 32, 58, 32, 114, 112, 98, 110, 98, 109, 102, 109, 103, 100, 109, 114";
const solution = code.split(",").map(element => String.fromCharCode(parseInt(element))).join("");
console.log(solution);
```
