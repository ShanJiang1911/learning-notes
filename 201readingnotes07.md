## Domain Modeling
* Domain modelling is basicly buildnig a model which contains entities and functions to solve a specific real world problem.
* Examples: model the popularity of epic fail videos.
* Examples: model the weekly popularity of epic fail videos by simply change a small part of the previous model.
* Build self contained objects with same attributes and methods when modeling  single entity.
* Try to use small methods focusing one job to get it done well
* Store newly created object in variable so you can access properties and methods from outside
* Use 'this' variable within methods so you can access properties and methods from inside



## From HTML book:

### Chapter 6: “Tables” (p126-145)
* What is table: kind of like excell. Show the content and numbers in grid format.
* Basic table structure:
  * < table >< /table >. To creat table. Put on top like < Doc!type HTML >.
  * < tr >< /tr >. Start and close each row.
  * < td >< /td >. Start and close each cell.
  * < th >< /th >. Table heading.
  * < td colspan="numbers" >< /td >. Span "numbers" columns in a row.
  * < td rowspan="numbers" >< /td >. Span "numbers" rows in a column.
* Long tables:
  * < thead >< /thead >. Headings of tables.
  * < tbody >< /tbody >. Body of tables.
  * < tfoot >< /tfoot >. Foot of tables.
* Old code: width & spacing, border & background

## From JS Book:

### Chapter 3: “Functions, Methods, and Objects” (pp.106-144)
* Creating an object:
```
const hotel = newObject {
    name:'indiana'
    age:3,
    'favorite toys':['root beer', 'mammoth', 'lollipop'],
    callHer:function(){
        console.log('Indiana! Come!');
    }
};
```
* Once created an object, user can always add properties to it
* For deletion, simply put word 'delete' before the notation
* Keyword "this" is commonly used inside object
* Global scope or clobal context: when function is created at the top level of a javascript
* Storing Data: Variables; arrays; individual objects; multiple objects
* Arrays are special types of obejct
* Arrays of objects & objects in arrays
* Build-in objects:
  * Browser object model
  * Document object model
  * Global Javascript objects
* Simple/Primitive Data types: 
  * String 
  * Number
  * Boolean
  * Undefined
  * Null
* Comples data type: object
* Number object
  * isNaN(). Check if the value is not a number
  * toFixed(). Rounds to specified number of decimal places
  * toPrecision(). Rounds to total number of places(returns a string)
  * toExponential(). Returns a string representing the number in exponential notation
* Math object
  * Math.PI.
  * Math.round()
  * Math.ceil()
  * Math.floor()
  * Math.random()
```
  function getRandomInt(max) {
  return Math.floor(Math.random() * max);
}
```
* Data and time object
```
let today = new Date()
```

[<--Back](README.md)