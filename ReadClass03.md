## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
* What does .map() return?
  * .map() can follow the use's instruction to take the values of an original array then return a new array with new values.
* If I want to loop through an array and display each value in JSX, how do I do that in React?
  * Return the resulting array of elements to ListItems, put them inside a < ul > element, then render it to the DOM.
* Each list item needs a unique __Key__.

* What is the purpose of a key?
  * Keys help React to identify which items have changed, added, or been removed.

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

* What is the spread operator?
  * "...", can expand an iterable object into the list of arguments.

* List 4 things that the spread operator can do.
  * Copying an array
  * Using Math functions
  * Adding an item to a list
  * Combining objects

* Give an example of using the spread operator to combine two arrays.
 * ```
    const arrOne = [1,2,3]
    const arrTwo = [4,5,6]
    const arrThree = []...arrOne, ...arrTwo]
    console.log(arrThree)
   ```


* Give an example of using the spread operator to add a new item to an array.
  * ```
    const fewFruit = ['apple','banana']
    const fewMoreFruit = ['watermelon', 'pineapple', ...fewFruit]
    console.log(fewMoreFruit)
    ```
* Give an example of using the spread operator to combine two objects into one.
  * ```
    const objectOne = {panda, bear}
    const objectTwo = {tiger, deer, monkey}
    const objectThree = {...arrOne, ...arrTwo}
    console.log(objectThree)
    ```

## [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

* In the video, what is the first step that the developer does to pass functions between components?
  * create a function wherever the state is we are going to change

* In your own words, what does the increment function do?
  * Pass the "add" function to parents object so it can show the results
* How can you pass a method from a parent component into a child component?
  * this.props.methodNeedToPass()

* How does the child component invoke a method that was passed to it from a parent component?
  * trigger by event

### [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
### [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

## Thins I want to know more about
* 


[<--Back](README.md)