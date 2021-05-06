## HTML book:
### Chapter 4: Ch.4 “Links” (pp.74-93)
* Link format: 
    ```
    <a href="http://www.xxx.com">XXXsite</a> 
* Link types: 
    * to other sites: use absolutly URL. ex: http://www.xx.com
    * to other pages on the same site: 
    ```
    <a href="index.html">home</a>
    ```
    * Link from one part to another part on the same page:
    ```
    <a href="#idName">idName</a>
    ```
    * Email link: 
    ```
    <a href="mailto:John@gmail.com">Email John</a>
    ```
    * Opening link in a new window:
    ```
    <a href="http://www.xxx.com" target="_blank">YouNameIt</a> (opens in new window)
    ```
    * Relative URLs: 
        * Same foleder: "review.html"
        * child folder: "music/listing.html"
        * grandchild folder: "movie/dvd/reviews.html"
        * parent folder: "../index.html"
        * grandparent folder: "../../index.html"
* URL= Uniform Resource Locator 


### Chapter 15: “Layout” (p358-404)(focus p358-364)
* Building blocks: a certain area on the page
    * Block-level elemetns: < h1 >, < p >, < ul >, < li >
    * Inline elements: < img >, < b >, < i >
* Containing elements: orter box which can contain several box level elements
    * < div > & < body > elements
* Controling the position of elements
    * Normal flow
    * Relative positioning
    * Absolute positioning
    * Fixed positioning
    * Floating elements
    * z-index can help user control which box appears on top


## JS book:

### Chapter 3 (first part): “Functions, Methods, and Objects” (p86-99)
* A function is like a tiny reusable software user created to perform a specific task. User can simply embedded it's tag to a place then run it.
* A typical function:
```
function sayHello() {
    document.write(Hello!");
}
```
* In the case above, "function"=function keyword; "sayHello()"=Function name; "{the content between curly braces}"=code block
* Declaring functions that need information:
```
function getArea(width, height) {
    return width * height;
}
```
* In the case above, width and height called parameters
* User can get single or multipal values out of function, by change the statement in the code block
* User can name a function then call it later
* Anonymous function has no name, just use the function expression directly
* Immediately invoked function espressions(IIFE)
* Anonymos function and IIFE both can only use once
* Variable scope: the location where user declare a variable will decide where it can be used


### Article: “6 Reasons for Pair Programming”
* How does pair programming work: Driver drive the vehicle and navigator thinks the big picture
* Why pair program:
    1.  Greater efficiency
    2. Engaged collaboration
    3. Learning from fellow student
    4. Improve social skills
    5. Improve job interview readiness
    6. Work environment readiness


[<--Back>](README.md)