## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
* What is functional programming?
  * `Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia`
* What is a pure function and how do we know if something is a pure function?
  * It returns same result if given same arguments and does not cause any observable side effects
* What are the benefits of a pure function?
  * It's easier to test
* What is immutability?
  * It cannot be changed anyway
* What is Referential transparency?
  * pure functions + immutable data = referential transparency
  * A function always give same result for the same input

#  [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)
* What is a module?
  * A Javascript file
* What does the word ‘require’ do?
  * Bring in the path of the module that we require so we can use it in the file
* How do we bring another module into the file the we are working in?
  * var newNoduleName = require('./moduleName')
* What do we have to do to make a module available?
  * module.exports = ModuleThatShouldAvailable


## Things I want to know more about
* How to manage a huge amount of modules?
[<--Back](README.md)