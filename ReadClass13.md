## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
* In your own words, describe what each group of status code represents:
100’s = Telling client the header part of the request has been received
200’s = Success codes. Telling client the request was accepted
300’s = Redirection codes. Telling client what they requested have been moved
400’s = Error codes. Telling client the request was invalid.
500’s = Error codes. Telling client the request was invalid due to the server issue.
* What is a status code 202?
  * The request was accepted, but need time to process
* What is a status code 308?
  * Status code with showing the location of the resource
* What code would you use if an update didn’t return data to a client?
  * 204 No content
* What code would you use if a resource used to exist but no longer does?
  * 410 Gone
* What is the ‘Forbidden’ status code?
  * 403 Forbidden


Video: [Build A REST API With Node.js, Express, & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
* Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  * When we deploy the website we don't want it in our local host
* What is middleware?
  * code that runs when the server gets a request but before it gets passed to your routes
* What does app.use(express.json()) do?
  * let our server accept JSON as a body instead of a post element or get element
* What does the /:id mean in a route?
  * means that this is a parameter that we can access by typing request.params.id, which would give us access to whatever passed in after the slash
* What is the difference beween PUT and PATCH?
  * PATCH can just only update what user passes but PUT would update all the information
* How do you make a defalut value in a schema?
  * default: Date.now
* What does a 500 error status code mean?
  * means there is an error on your server
* What is the difference between a status 200 and a status 201?
  * 201 means successfully created an object. If yo don't send 201 by default it will send 200 which means everything was successful


## Things I want to know more about
what is nodemon

[<--Back](README.md)