#Prototype pollution
<p>&nbsp;</p>

```Прототип это обьект в JS, на который ссылается другой объект для наследования свойств и методов```
<p>&nbsp;</p>

```js
let myObject = {};
console.log(Object.getPrototypeOf(myObject));  // Object.prototype

let myArray = [];
console.log(Object.getPrototypeOf(myArray));   // Array.prototype

let myString = "Hello";
console.log(Object.getPrototypeOf(myString));  // String.prototype
```
![image](https://github.com/user-attachments/assets/649b598d-a3ec-4519-88cd-d46fa93db20b)
