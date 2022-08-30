

100’s = Informational Codes 
200’s = Completed/ Everything is fine 
300’s = rediriection
400’s = Error
500’s = Server not being able to reicive information 
- What is a status code 202? Everything is completed, good to go
- What is a status code 308? Redirection to some other location
- What code would you use if an update didn’t return data to a client? 204
- What code would you use if a resource used to exist but no longer does? you would use 400s, 410
- What is the ‘Forbidden’ status code? 
The forbidden code is when you do not have right access to the source


- Why do we need to pull our MongoDB database string out of our server and put it into our .env? You have to pull MongoDB database string out of our server and put it into our .env because pulling out the data from local is not wanted rather you want to pull the data from the server.
- What is middleware?
code that runs between server and user request.
- What does app.use(express.json()) do?
It lets server decide upon using express.json as the body of the app
- What does the /:id mean in a route?
Request.Params.id
- What is the difference between PUT and PATCH?
Put is for a new user, like putting in a new information and patch is updating already exisiting data
- How do you make a default value in a schema?
by using JS object
- What does a 500 error status code mean?
It means code can not be reached because server is about to explode
- What is the difference between a status 200 and a status 201?
200 general accpeted, 201 specific status upon accpeted.