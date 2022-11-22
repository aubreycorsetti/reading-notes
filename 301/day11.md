# Day 11 Notes

## CRUD

### Status Codes Based On REST Methods

• In your own words, describe what each group of status code represents:

  > 100’s = information status codes, they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client
  > 200’s = These are the success codes. They tell the client that its request was accepted.
  > 300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.
  > 400’s = These are the client error codes. They are all about invalid requests a client sent to a server.
  > 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server

• What is a status code 202?
  > Status 202: Accepted. This code tells the client that the request was valid, but its processing will finish sometime in the future.
• What is a status code 308?
  > Status 308: Permanent redirect. This tells the client to use another URL to access the resource and not use the current URL anymore.
• What code would you use if an update didn’t return data to a client?
  > Code 204: No content
• What code would you use if a resource used to exist but no longer does?
  > 410: Gone
• What is the ‘Forbidden’ status code?
  > 403: Forbidden, the client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

### Build A REST API With Node.js, Express, & MongoDB

• Why do we need to pull our MongoDB database string out of our server and put it into our .env?

  > To make sure we can use something other than our local host.

• What is middleware?

  > It's a software that provides common services and capabilities to apps outside of the operating system

• What does app.use(express.json()) do?

  > It parses the incoming requests with JSON

• What does the /:id mean in a route?

  > It's the path that get you to the specified function

• What is the difference between PUT and PATCH?

  > PUT alters resources when the client transmits data for the whole resource. PATH transforms the resources and transmits partial data.

• How do you make a default value in a schema?

  > const schema = new Schema({type: String})

• What does a 500 error status code mean?

  > 500: generic error response, the server encountered an unexpected condition

• What is the difference between a status 200 and a status 201?

  > 200: request is understood, received and processed.
  > 201: request was successful and a resource was created as a result.

### Things I want to know more about

> I would like to memorize the codes better

Click to return [Home!](../README.md)
