## Understanding The Problem Domain Is The Hardest Part Of Programming
* The author thought Problem Domain si the hardest part of programming
* Why problem domain is hard? It's like put a puzzle together but have no pic on hand
* If you know the whole picture(problem domain), programming will be easier for you
* What we can do?
  * Make problem domain easier
  * understand the domain better

## From JS book

### Chapter 3: “Object Literals” (pp.100-105)
* What is object?
  * A set of variables and functions to create a model to solve realworld problems
* In an object: 
  * Variables called Property. Like hotel name, room number.
  * Function called method. Task you want to conduct. like calculate reservation rate.
  * They both called Key in an object. No same name key in an object.
* In JavaScript:
  * Variables have a name and user can assign them a value: String, number or bollean
  * Arrays can have a group of values
  * Named functions can run a set of statements when get called
  * Object consist of a set of key/value pairs
* Creating object: Literal notation
```
let hotel = {
    name:'Hotel California',
    rooms: 50,
    booked: 25,
    checkAvailability: function(){
        return this.rooms -this.booked;
    }
};
```

### Chapter 5: “Document Object Model” (pp.183-242)
* Document Object Model is a separate set of rules by major browers covering two areas:
  * Making model of the HTML page
  * Accessing and changing the HTML page
  * Also called API
* DOOM tree ii a model of a web page
* Dom tree:
  * Document Node
  * Element Nodes
  * Attribute Nodes
  * Text Nodes
* Accessing elements:
  * Return single element: getElementById('id')
  * Return single element: querySelector('css selector')
  * Return one or more elemtns: getElemetnsByClassName('class')
  * Return one or more elemtns: getElementsByTagName('tagName')
  * Return one or more elemtns: querySelectorAll('css selector')
* Method select individual elements:
```
document.getElementById('one')
```
* Repeating actions for an entire nodelist
  * 
  ```
  let hotItems = document.querySelectorAll('li.hot');
  for(let i=o; i< hotItems.length; i++) {
      hotItems[i].className = 'cool';
  }
  ```
* Two approaches to adding and removing content from a DOM tree:
  * innerHTML property
  * DOM manipulation
* Cross-site Scripting(XSS) attacks
* Defending Against cross-site scripting
* Attribute Nodes
  * getAttribute()
  * hasAttribute()
  * setAttribute()
  * removeAttribute()

  [<--Back](README.md)