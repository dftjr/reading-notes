# Class-03 Notes

<br>

## HTML Notes
**When should you use an unordered list in your HTML document?**
 
- You should use an unordered list when the order of how they're listed is meaningless and doesn't really have a purpose.
 
**How do you change the bullet style of unordered list items?**

- Using <code>list-style-type</code>

**When should you use an ordered list vs an unorder list in your HTML document?**

- You should use an ordered list when the order of the items listed is of inportance and has meaning.

**Describe two ways you can change the numbers on list items provided by an ordered list?**

- You can use <code>type</code> to change them to Roman Numerals
- You can use <code>start</code> to decide what number the list starts on
- You can use <code>reversed</code> to reverse the order of the numbers

<br>

## CSS Notes
**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**

- In the story "The Box Model" two out of the four main characters, Marg and Paddy, play an inportant role in defending the castle where the Content king reigns.
Paddy was responsible for keeping the invaders at a certain distance from the castles walls, this insured that Paddy control the battle the way the king wanted. 
Margg was in charge of keeping the King a certain distance away from the same walls depending on how fierce the battles became to protect the king from harm.

**List and describe the four parts of an HTML elements box as referred to by the box model.**

- margin
  - The invisible space around the box. This pushes away other elements around it.
- border
  - This adds a border around your element, it lies between the margin and padding. The standard box model adds the width and hieght to the box.
- padding
  - Sitting between the border and the area containing the content, this is used to push the content away from the border.
- content
  - This is the section where the content is displayed.

<br>

## JS Notes
**What data types can you store inside of an Array?**

- strings
- numbers
- objects
- other arrays
*You can also mix and natch different data-types*

**Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

- It is a valid array!
  - You can access it by using <code>console.log(people)</code> to see all the values in the array.
  - You can use <code>console.log(people [i])</code> replacing the <code>i</code> with whatever number you would like to use to pull the data held in that part of the array.
    - ex. <code>console.log(people [1])</code> would pull Smith's information form the code.

**List five shorthand operators for assignment in javascript and describe what they do.**

- Logical AND assignment: <code>x &&= f()</code>
  - Operator only assigns if the <code>x</code> value is true.
- Logical OR assignment: <code>x ||= f()</code>
  - Operator only assigns if the <code>x</code> value is false.
- Multiplication assignment: <code>x *= f()</code>
  - This operator multiplies a variable by the value on the right side, assigns a new result to the variable.
- Division assignment: <code>x /= f()</code>
  - This operator divides a variable by the value on the right side, assigns a new result to the variable.
- Subtraction assignment: <code>x -= f()</code>
  - This operator subtracts a variable by the value on the right side, assigns a new result to the variable.

**Read the code below and evaluate the last expression and explain what the result would be and why.**

- The response that comes back is <code>10dog</code>
  - Because the data types are different, the code will add them together into the output by sticking them next to each other, but it cannot physically add the values together.

**Describe a real world example of when a conditional statement should be used in a JavaScript program.**

- Conditional statements are best used when deciding what code should be executed when certain values are presented and/or met.
  - ex. You are creating a code that will output a persons personal information that they have saved to a file, but you want to make sure that that data is not presented to the user unless all the conditional fields are met. If they are not met, the conditionals would reject the process. Sort of like when you get a password wrong.  

**Give an example of when a Loop is useful in JavaScript.**

- A loop would be useful when you have something that needs to repeat itself over and over again, for example if you need to find out different outcomes.
  - ex. You're creating a program to see what the house odds are when playing certain hands in a BlackJack game.


## Things I want to know more about
