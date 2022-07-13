# Class 01 Reading Overview & Notes

<br>

## How does HTTP work?

- HTTP (Hypertext Transfer Protocol) is anplcation protocol that defines the language for clients are servers to speak to each other. The browser locates the DNS server, the browser then sends a HTTP request to the server. This request is asking for a copy of the website to send to the client. It gets sent across the internet using TCP/IP. If the server approves, it starts sending the client the website files in return. After all data is assembled, the webpage is displayed.

<br>

## Getting Started

**Describe how HTML, CSS, and JS files are parsed in the browser**

- The browser parse te HTML first, recognizes any <code>link</code> elements from CSS and any <code>script</code> elements from JavaScript. The browser generates an in-memory DOM from the parsed HTML. It then generates a CSSOM structure from the parsed CSS.

**How can you find images to add to a Website**
  
- You can find images all over the internet! You just have to make sure they are free-use OR that you have the license (or agreement from the owner) to use said images due to copywrite laws.

**How do you create a String vs a Number in JavaScript?**

- Strings have <code>' '</code> wrapped around the text.
    - ex. <code>let anyVariable = 'any string';</code>
- Numbers do not have <code>' '</code> wrapped around the number. 
    - ex. <code>let anyVariable = 1;</code>

**What is a Variable and why are they important in JavaScript?**

- They are containers that store values. You do this by using the <code>let</code> keyword followed by whatever variable name you choose to store the data in.

<br>

## Introduction to HTML

**What is an HTML attribute?**

- Attributes don't show up in the code, they contain pieces of extra information about the element.

**Describe the Anatomy of an HTMl element**

- An opening tag, the content, and a closing tag
  
**What is the Difference between <code>article</code> and <code>section</code> element tags?**

- Section represents a standalone section of the document
- Article is a self-contained composition in a document, something that is intended to be reusable

**What Elements does a “typical” website include?**
  
 - The typical elements are:
    - <code>header</code>
    - <code>nav</code>
    - <code>main</code>
    - <code>footer</code>
    - <code>body</code>

**How does metadata influence Search Engine Optimization?**

- It helps with search engines, as it will be the information that is pulled in displayed by the person searchign for it

**How is the <code>meta</code> HTML tag used when specifying metadata?**

- It's the way of describing the data 
  
<br>

## How to start to design a Website

**What is the first step to designing a Website?**

- Brainstorm notes on the purpose and design of the site, create a rough sketch/drawing of how it will be structured

**What is the most important question to answer when designing a Website?**
  
- What exactly is it that you want to accomplish with the website
  
<br>

## Semantics

**Why should you use an <code>h1</code> element over a <code>span</code> element to display a top level heading?**

- <code>h1</code> give the text inside it a meaning as being an important header of information on that page. This is very crucial when it comes to search engine websites pulling information.
- <code>span</code> this is an inline container that contains generic information, this does not inherently represent anything specific.

**What are the benefits of using semantic tags in our HTML?**

- It gives the purpose or reason for that piece of code
  
<br>

## What is JavaScript?

**Describe 2 things that require JavaScript in the Browser?**

- Anything on a webpage that is dynamic or that control multimedia

**How can you add JavaScript to an HTML document?**
  
- It can be added by using the helpful <code>script</code> element

<br>

## Things I want to know more about
