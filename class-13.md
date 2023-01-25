# Reading - Class 13

This will briefly cover local storage and how to use it on websites

## Local Storage

1. **Why would a developer use local storage for a web application?** Because the websites that we visit are stateless meaning that when web pages &/o applications are opened and then closed in a browser, the information it holds and displays will be reset every time it's refreshed. We can use local storage as a way to save some of this information so that everything does not need to be renewed/reloaded when a page or application is refreshed. One common way that this happens is by the use of cookies which are text files that are saved on a user's computer that stores relevant infromation for a webpage.

2. **What information should not be stored in local storage?** We should not store any sensitive data in local storage as things like cookies can be used to spy on people and attack vulnerabilities in your browser/machine.

3. **Local storage can store what type of data? How would you convert it to that type before storing?** Local storage only stores strings. If we have something that is a non-string, such as an object, we can convert that to a string using `JSON.stringify()` and give it an argument of the object that we want to store.

`localStorage.setItem('car', JSON.stringify(car) );

and when we want to get that information we can use `JSON.parse()`, e.g.

JSON.parse( localStorage.getItem( 'car' ) );

## Things I Want To Know
- What are some of the guidelines / best practices for storing things in local storage.