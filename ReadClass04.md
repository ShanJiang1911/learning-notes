## [React Docs - Forms](https://react-bootstrap.github.io/components/forms/)
* What is a ‘Controlled Component’?
  * An input form whose value is controlled and readered by React.
* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  * Since react handle changes on every keystroke, the display value will update as soon as user types in.
* How do we target what the user is entering if we have an event handler on an input field?
  * We can add a name attribute to each element and let the handler function choose what to do based on teh value of the event.target.name.
## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
* Why would we use a ternary operator?
  * Ternary operator can accomplish test in just one line of code which may take several lines of code if we use if statement

* Rewrite the following statement using a ternary statement:
  ```
  if(x===y){
    console.log(true);
  } else {
    console.log(false);
  }
  ```
  ```
  Rewrite:
  (x===y) ? true : false
  ```



### [React Bootstrap - Forms](https://react-bootstrap.github.io/components/forms/)
### [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about
* The syntax of React


[<--Back](README.md)