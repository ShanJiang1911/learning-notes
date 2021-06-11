## [React Docs - thinking in React](https://reactjs.org/docs/thinking-in-react.html)

* How would you break a mock into a component heirarchy?
  * Draw boxed around every component and name them. Or talk with your designer who created it(if you have one).

* what is the single responsibility principle and how does it apply to components?
  * A component should only do one thing. If it ends growing up, it should decomposed to smaller subcomponents.

* What does it mean to build a ‘static’ version of your application?
  * Which means to build a version that takes your data model and renders the UI but has no interactivity.

* Once you have a static application, what do you need to add?
  * Probably I will add state.

* What are the three questions you can ask to determine if something is state?
  * >1. Is it passed in from a parent via props? If so, it probably isn’t state.
    >2. Does it remain unchanged over time? If so, it probably isn’t state.
    >3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
    >><cite>https://reactjs.org/docs/thinking-in-react.html</cite>

* How can you identify where state needs to live?*
  * >Identify every component that renders something based on that state.
  * >Find a common owner component (a single component above all the components that need the state in the hierarchy).
  * >Either the common owner or another component higher up in the hierarchy should own the state.
  * >If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
  * >><cite>https://reactjs.org/docs/thinking-in-react.html</cite>
  

## Things I want to know more about
Learn more about the react syntax

[<--Back](README.md)