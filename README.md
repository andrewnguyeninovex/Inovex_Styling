![This is an image](Inovex-logo.jpg)
# Inovex Best Practice :blush:


<br/>
## Eslint

Indentation
```js
<-- 4 Spaces -->
value: {
--> actual: 0,
    maxValue: 0,
    minValue: 0,
    low: 0,
    showActual: true,
    value: 0
    }
```

File Extensions
```js
ShoppingCart.tsx // [tsx] for components
ShoppingCartProps.ts // [ts] for interface, utility, stateless functions
GetShoppingCartData.js // [js] for files that don't require typescript
```

Quotations
```js
<-- OK -->
import "./ExampleComponent.scss";
```
```
<-- NOT OK -->
import './ExampleComponent.scss';
```

Arrow Functions

Variable Definition



## CSS Guide


<br/>
## Component Decision Making
Always create components with **reusability in mind**.
Will the component contain states? Will it handle prop manipulation or just take in data?
Determine if it's going to be a static component that has nothing but the bare minimum. Pizza dough without the topping.

Treat components like lego blocks :bricks:


<br/>
## Debugging Tips

### console.log
```js
<-- The sweet sweet console.log -->
console.log("Hello World");
console.log("%cHello World", "color: red"); // You can add styling to your logs with %c - optional parameter applies CSS
```
![image](https://user-images.githubusercontent.com/102827542/168629196-e6c77727-2c5f-4b59-b77a-b948bbd2c8c5.png)

### console.dir
```js
<-- console.dir is great to show the print in object form -->
let objectA = {name: "Inovex", location: "Oakville"};
console.dir(objectA);
console.log(objectA);
```
![image](https://user-images.githubusercontent.com/102827542/168636345-2d7ccd8a-7d7b-4c18-899e-e7dd5708a96d.png)
<br/>
`Key difference is the fact log returns the object in string representation and dir recognises the object just as an object and output its properties which can be navigated in tree structure.`

### console.table
```js
<-- console.table illustrates the array in table format -->
let arrayList = [1, 3, 5, 7, 9];
console.table(arrayList);
```
![image](https://user-images.githubusercontent.com/102827542/168632320-5ec062b1-baaa-459c-9b64-d203cac11ac0.png)

### console.assert
```js
<-- console.assert will trigger a message if the condition is not satisfied -->
let a = 1;
let b = 2;
console.assert(a === b, {a, b, errorMsg: "They do not match"});
```
![image](https://user-images.githubusercontent.com/102827542/168632848-9b7d494d-d331-4017-b5a6-785f3d7a2f83.png)
<br/>
`You can see that the functions and calls are listed to help you step back on which functions were used before the assert was triggered.`

### console.error, console.warn
```js
<-- Display Red and Yellow blocks on console for visibility. -->
console.error("Red warning"); // You can throw in try/catch as well conditional codes (similar to assert)
console.warn("Yellow warning");
```
![image](https://user-images.githubusercontent.com/102827542/168633201-b069882d-9a9e-4693-a0b9-bee099506971.png)

### console.time, console.timeEnd
```
console.time() // Time in
console.timeEnd() // Time out
```
![image](https://user-images.githubusercontent.com/102827542/168637565-877deda4-315b-452e-ac8d-bf6b5e4af443.png)
<br/>
`Place the time and timeEnd before and after line of codes you'd like to diagnose. This will help check how long code runs`

### debugger
```js
<-- Will open up debugger tool on browser; similar to placing breakpoints to step in/over code -->
debugger;
```
![image](https://user-images.githubusercontent.com/102827542/168633984-88dfa52c-28d0-46bf-83c9-876451cbc350.png)
<br/>
`You can view all the stored data in scope and additional details from call stacks, file issue, line of code, and more.`


<br/>
## Folder Structure

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
 ```
 
 
 <br/>
### Help

https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

https://google.github.io/styleguide/htmlcssguide.html

https://github.com/airbnb/javascript
