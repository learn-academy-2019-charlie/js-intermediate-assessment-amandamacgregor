# Intermediate Javascript Assessments

### Without using Google answer the following:

1. What is the difference between .map() and .filter()?

.map() affects each element in an array and returns the same number of elements
.filter() acts as a 'funnel', returning only those elements that meet our conditions.

2. Why would you use object destructuring?

To almost create a 'shorthand' to increase usability of key value pairs.  To take a line of code like this.family.person.pet and assign whichever part of that to it's only variable than can be called without all those .'s

3. What is the difference between var, let, and const?

var is typically a global variable, let is local in scope, and const is a variable that can't be changed.

4. Why is testing important?

It provides a blueprint for expected outcomes of each part of a program; when something breaks, how it breaks should help pinpoint where in the code the issue is.

Costs moe up front, but can save gobs of money down the road regarding downtime sine pinpointing and thorough testing suites will speed up corrective measures.

Testing can help build the program itself in slices, providing structure and reducing scope (or keeping you on track and not encouraging scope-creep)

5. What is a higher order function?

.map() and .filter() are examples of higher-level functions.  They are functions that use other functions as arguments.


6. What is the difference between a class and an object?

Class is a template/blueprint for an object.

7. What did you learn during the group project this week? Please include any additional feedback you may have.

The group project was really difficult; I was in the group of 4.  The biggest lesson was to keep re-engaging even when I felt shut down with my desire to use testing to help us, or practice the more recent higher-level functions we learned before tackling it.  I found a couple of my partners would rather talk things through past the point of abstract before typing, trying to even googling things.  Reading the group and finding the right time to re-state a suggestion was useful to ultimitely getting things done, but was thoroughly exhausting! I'm not sure I learned much at all technically until seeing the demos of other groups.

### HTML/CSS Review questions: First, try to answer each question on your own then Google the answer to further your knowledge.
**I had to google most of these; I'm fuzzy at best.
1. How do you link a CSS file to your HTML page?

<head>
    <title>Title</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
</head>

2. What is the difference between a div and a span?

The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

3. What is a CSS class? When should you use an id instead of a class?

Both are hooks.

Classes are NOT unique: class="myClass"
You can use the same class on multiple elements.
You can use multiple classes on the same element.

ID's are unique: #myHeader
Each element can have only one ID
Each page can have only one element with that ID;
JavaScript depends on there being only one page element with any particular id

4. Name 4 semantic HTML tags.

<header>
<footer>
<main>
<nav>

5. What are three options for creating responsive design?

Media queries
Fluid grids
Flexible images
**I don't really understand the question though


### Stretch: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

My answer-
Front end is anything user-facing.  Tools would include HTML, CSS, JS, Bootstrap, React.

Google-
client-side development is the practice of producing HTML, CSS and JavaScript for a website or Web Application so that a user can see and interact with them directly

2. What is block scope in JavaScript?

My answer-
Block scope is a block of code, as in a function, where variables can be declared in a local capacity for that function and not accessible outside that function.

Google-
A block scope is the area within if, switch conditions or for and while loops. Generally speaking, whenever you see {curly brackets}, it is a block. In ES6, const and let keywords allow developers to declare variables in the block scope, which means those variables exist only within the corresponding block.

3. How would you explain the idea of "inheritance" in object oriented programming?

My answer-
Inheritance is the adopted behavior and data from parent classes as they pertain to child classes, or objects.

Google-
Inheritance enables new classes to receive—or inherit—the properties and methods of existing classes.
