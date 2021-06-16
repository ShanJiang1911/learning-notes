## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)


* What does REST stand for?
  * Representational State Transfer
* REST APIs are designed around a ____.
  * resource, which are any kind of object,data,or service that can be accessed by the client
* What is an identifer of a resource? Give an example.
  * It's a URI that uniquely identifies that resource. Example: `https://adventure-works.com/orders/1`
* What are the most common HTTP verbs?
  *  GET, POST, PUT, PATCH, and DELETE.
* What should the URIs be based on?
  * nouns(the resource) and not verbs(the operations on the resource)
* Give an example of a good URI.
  * `https://adventure-works.com/orders`
* What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  * API require a client application to send multiple requests to find all of the data that it requires. It's a bad thing.
* What status code does a successful GET request return?
  * 200
* What status code does an unsuccessful GET request return?
  * 404
* What status code does a successful POST request return?
  * 201
* What status code does a successful DELETE request return?
  * 204

[RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet

* How would you match your name using RegEx?
  * character set

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)



## Things I want to know more about

[<--Back](README.md)