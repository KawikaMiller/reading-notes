# Reading - Class 08

These notes will explain the basics of REST and the principles behind it

## API Design Best Practices

1. **What does REST stand for?** Representational State Transfer

2. **REST APIs are designed around a ____.** Resources - which are any kind of object, data, or service that can accessed by the client.

3. **What is an identifier of a resource? Give an example.** An identifier is a URL that uniquely identifies the resource. An example would be like a URL to a specific pull request that we've made on a repo.

4. **What are the most common HTTP verbs?** GET, POST, PUT, PATCH, DELETE

5. **What should the URIs be based on?** Nouns that represent the resource

6. **Give an example of a good URI.** `https://website.com/shop`

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?** "Chatty" web API's refer to how often web requests are being made to the web server - the more requests, the more chatty the API which also means that the server is taking on a bigger load. This is a bad thing that we typically want to avoid.

8. **What status code does a successful GET request return?** 200

9. **What status code does an unsuccessful GET request return?** 404

10. **What status code does a successful POST request return?** 201

11. **What status code does a successful DELETE request return?** 204

## What I Want To Know More About

- How do you know when an API is being too 'chatty'? Where can we see these metrics &/o what are common tools used to view/gather that data?