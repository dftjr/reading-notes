# Reading Note Class 09

<br>

## HTML Forms

**Why are forms so important in web development?**

- Forms are what allow users of the website to input valuable information, information that may be needed to exercise code as well.

**When designing a form, what are some key things to keep in mind when it comes to user experience?**

- Its good practice to keep everything sectioned and simple. If you can keep most forms to a single column it helps with keeping the users attention. Having things happen as well, buttons that interact with the users in puts, color changes, anythign that makes the form not feel as flat and static  

**List 5 form elements and explain their importance.**

- <code>label</code> is a formal way to define a description for the HTML form widget
- <code>fieldset</code> is used to group several controls, including <code>labels</code>, within a form
- <code>input</code> is used for receiving the data being input by the user
- <code>option</code> defines an option in the form that can be selected
- <code>textarea</code> defines multi-line input field

<br>

## Introduction To Events

**How would you describe events to a non-technical friend?**

- Its something that triggers something else to happen, for example, if i turn the key in the ignition of mm car, that starts a chain reaction of events that then produces the outcome with is the car turning on.

**When using the addEventListener() method, what 2 arguments will you need to provide?**

- First argument is to listen for the data input
- Second argument is to inititate an event after said

**Describe the event object. Why is the target within the event object useful?**

- Events that occur in HTML unltamatley belong to an event object, they inherit all of their properties and methods
- The event target returns the element that triggered the event, so it's helpful in knowing what data shoul dbe being received and then sent back out

**What is the difference between event bubbling and event capturing?**

- Bubbling: when an event happens to an element it runs in this order 1. handles itself 2. handles the parents 3. handles the ancestors
- Capturing: has 3 phases- 1. event goes to the element 2. event reaches the element 3. event then comes back up the chain of events

<br>

## Things I want to know more about
