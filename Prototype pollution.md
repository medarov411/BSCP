#Prototype pollution
<p>&nbsp;</p>

```Прототип это обьект в JS, на который ссылается другой объект для наследования свойств и методов```
<p>&nbsp;</p>

```let myObject = {};```
```console.log(Object.getPrototypeOf(myObject));  // Object.prototype```

```let myArray = [];```
```console.log(Object.getPrototypeOf(myArray));   // Array.prototype```

```let myString = "Hello";```
```console.log(Object.getPrototypeOf(myString));  // String.prototype```
