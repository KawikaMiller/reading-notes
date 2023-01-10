# Readings - Class 01

This topic is important because it covers the basics of web development. It explains how/why HTML, CSS, and JavaScript work individually as well as how they work together in order to create a webpage.

## Getting Started

1.
```
I first need an address, but where should I look?
Ah yes, I'll look here in my web address book!
I walk to the Server house, ask for information. 
They say "Sure, Mr. Client, copy without hesitation!"
I arrive back at home and I am quite astounded
By all of the content as I continue to browse it
```

2. HTML is parsed first so that the browser can recognize any `<link>` &/o `<script>` elements. As the HTML is parsed, requests are sent back to the server for any CSS &/o JavaScript files and then parses those. The browser then generates a DOM tree for the HTML, CSSOM for the CSS, and compiles and executes the JavaScript. As everything is being built, the website starts to be visualized on the screen so that the user can see the content and interact with it.

3. We can add images to a website by using the `<img>` tag and giving it an `src` attribute. The `src` attribute's value must be a valid path to the image you want to display which either on another website, `htttp://www.awebsite.com/apicture.jpg` or somewhere within the current website's directories, `./images/anotherpicture.jpg`.

4. After we declare our variable with `let`, `const`, or `var`, we would either give it the value of `'44'` if we wanted it to be a `string` or `44` if we wanted it to be a number. A `string` is wrapped in either single quotes `''` or double quotes `""` and a `number` is not wrapped in quotes and must only use numeric characters. 

5. A `variable` is essentially a container that holds information. We give the container a name that represents what kind of in information is being stored inside. They are important because the information inside of a variable can be changed when we need it to be and they can also act as a shorthand for long-winded information. For example, we can store the information "Hi, my name is Kawika." as a variable named `greeting`, and then we don't need to type out the entire greeting everytime we need it, we can just simply use the `greeting` variable instead. This allows us to create dynamic content for our websites and web applications.

## Introduction to HTML

1. An attribute is almost like a hidden, pre-named variable for an HTML element. It allows us to give extra context &/o information to our elements. We can give elements a `class` attribute, or an `id` attribute to help identify it and it's content, or use the `a` and `href` attributes to create a working hyperlink. We can also give images and videos `height` and `width` attributes to specify how big they should be. 

2. An HTML element is composed of its tags and their content. A tag has two angle brackets `<>` that contain the keyword for whatever tag it is that we are creating, for example `<body>` or `<div>`. Sometimes these tags require opening (`<body>`) and closing (</body) tags, where the closing tag has a forward slash after the first angle bracket `<` but before the element keyword. Some tags are also self closing, like `<img/>`, which has the forward slash `/` before the last angle bracket `>` but after the keyword. Additionally, an HTML element can also have attributes &/o content between the opening and closing tags. For example `<p id='blurb'>Some text goes here.</p>` or `<img src='./images/picture.jpg' alt='this is a picture' />`

3. An '<article>` is a block of related content that makes sense on its own without the rest of the web page, for example just a single blog post. A `<section>` is similar but it's more for grouping together various pieces of information into a single part, like a series of headings with a quick summary about each.

4. A "typical" website usually has a `<head>` element which contains all the metadata, a `<body>` element which contains the `<header>`, `<main>` and `<footer>` elements. The `<header`> will typically contain things like the `<nav>` element, while the `<main> element will contain things like `<div>`s, `<p>`s, `<section>`s, etc, and the `<footer>` will usually contain things like copyright information or related links.

5. A search engine will scan the information in a website's metadata and can potentially make your webpage appear higher in the relevant search results. We can give a `<meta>` tag the `name` attribute with a value of `description` and then also give it a `content` attribute and whatever value we assign that will appear as the little text blurb underneath the hyperlink displayed in the search results which will also influence the search engine.

6. The `<meta>` tag is included within the `<head>` element of an HTML document and is the "official" way of adding metadata to a document. It can be used to specify things like character encoding, the title &/o author of the page, to give it a content description that displays with the search results, etc.

## Miscellaneous

1. The first step to designing a website is *project ideation*, which is a fancy way of deciding:
	- What do I want to accomplish?
	- How will a website help me reach my goals?
	- What needs to be done, and in what order, to reach those goals?

2. The most important question to ask yourself is **What exactly do you want to accomplish?** This will help to guide you throughout the rest of the process of creating your website by helping you determine what individual tasks/milestones you need to achieve in order to reach the end goal of having a fully functioning website.

## Semantics

1. Its important to use semantic HTML when creating your website. For example, using an `<h1>` element instead of a `<span>` element is preferred because an `<h1>` element has an inherent meaning to it. When we see `<h1>` in our HTML document we know that it's typically used to designate a "top level heading" on our webpage, wheras if we use a `<span>` it does not have any of that inherent semantic meaning to it and we would have to style it ourselves in order for it to give off the appearance of a "top level heading" by changing it's style and increasing the font-size, etc.

2. The benefits of using semantic HTML is that it helps to give us context as to what each element is supposed to represent in the document. For example, we could create a bunch of `<div>`s on a webpage that hold all the correct information and are in their correct hierarchal position, however when we quickly glance over the document we have no idea what each `<div>` is supposed to represent and what it's content is without further examining the actual content of the tags. When we use semantic HTML we know that the `<header>` will contain the `<nav>`, the `<main>` will contain the main focus of the webpage, and that the `<footer>` will contain the copyright information and any additional related links. Additionally, seach engines will also consider imporant keywords taht influence the page's search rankings and screen readers can help visually impaired people navigate a website better. 

## What is JavaScript?

1. Two things that require JavaScript in the browser are APIs and event listeners. If we want to make API calls we need to do so through JavaScript code. We can use Browser APIs, like the DOM API, to dynamically manipulate our website or we can also use third party APIs like Twitter API or Spotify API in order to send/receive information like displaying our most recent tweets or creating a new playlist, respectively. Event listeners can be used to fire off functions when we do things like click a button or hover over an element. For example, we might want to change a color of an element when we click a button or display an image when we hover over an element.

2. We can add JavaScript to our HTML document by using the `<script>` element. We can either create an internal JavaScript element by typing the JavaScript code between opening and closing `<script>` tags, or we can link to an external JavaScript file by giving a `<script>` element the `src` attribute with a value of the relative path of the JavaScript file, such as `<script src="myScript.js"></script>

## Things I want to know more about
- More practical / real world examples about `<article>`, `<section>` and `<aside>`
- How exactly does Search Engine Optimization work and what is the process it takes when scanning a web page for meta data
