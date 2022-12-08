# Class-07 Notes

<br>

## Domain Modeling

**Explain why we need domain modeling.**

- The process of creating a conceptual model in code for a specific problem. It helps validate the understanding of the problem that is at hand.

<br>

## HTML Table Basics

**Why should tables not be used for page layouts?**

- They reduce the accessibility for visually impaired users
- Makes code harder to debug and maintain, tables require more complex structures
- Must take extra measures to get table to style for all varities of devices. HTML itself defaults 100% to their parent element

**List and describe 3 different semantic HTML elements used in an HTML <code>table</code>**

- <code>th</code>: Recognizes the elements as headers, visually and semantically
- <code>td</code>: The data cell inside a table
- <code>tr</code>: The row that the data cells sit in

<br>

## Introducting Constructors

**What is a constructor and what are some advantages to using it?**

- A constructor function is made to store the data values that will referenced when applying it to an exsisting object. This is useful for saving memory and also reducing the amount of code iterations that the computer/program have to run through.

**How does the term <code>this</code> differ when used in an object literal versus when used in a constructor?**

- Inside of an object it is referring to the data inside the object itself
- Inside of a constructor, it is referring to the data inside of the object you are attaching it to, not the data inside the constructor

<br>

## Object Prototypes Using A Constructor

**Explain prototypes and inheritance via an analogy from your previous work experience.**

- My understanding is that object properties and methods can be shared through generalized objects. They can be cloned and extended. 
- I would say it relates to, me working a job with a bunch of tasks to get done, then my boss comes in and gives me additional tasks that I'm not normally suppose to have, but that i've now been inherited
