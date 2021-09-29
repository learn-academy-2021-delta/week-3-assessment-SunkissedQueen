# ASSESSMENT 3: Interview Practice Questions

Answer the following questions.

First, without external resources. Challenge yourself to answer from memory as if you were in a job interview.

Then, research the question to expand on your answer. Even if you feel you have answered the question completely, there is always something more to learn. Write your researched answer in your OWN WORDS.


1. What is `this` in JavaScript?

  Your answer: `this` in JavaScript helps call upon a value in a key:value within a class. When you want the exact value that was input, you will use a structure as such `this.number: number` in the class. In the code block, `this.number` makes the value reusable.

  Researched answer: `this`---More than just a four-letter word! The keyword `this` in JavaScript has different values depending on what object or environment to which it belongs. In the global arena, `this` refers to the global object. Within a function, it refers to what the function is calling. Inside constructors, it is the argument statement. When a method is being used, `this` refers to the object receiving a function call. Pay attention to `this` so you don't cause too much trouble with that other thing.



2. What is React? Why would you use it?

  Your answer: React is more places than I realized. Facebook has been very generous to the tech world. React allows a full stack approach to using Javascript syntax in coding and allow the DOM to present it to the world.

  Researched answer: Through the generosity of Facebook, the JavaScript library called React helps create webpages and mobile applications. React allows class components to work in isolation and be returned on the user interfaces by a render function. The components are reusable and dynamic. In my opinion, the separation of each component makes the project appear cleaner and less hectic. I think that it also reduces causing errors on code not pertaining to the assigned team.



3. Which lifecycle method is required in a React class component?

  Your answer: I recalled using the term while building and linking various files and components in the React application. The word `lifecycle` is making me think it is link to the parent-child inheritance. Time to research and refresh.

  Researched answer: The life cycle methods---mounting, updating, unmounting, and error handling----signify the common methods to use during various phases of creating, managing, or removing a React application. The render() method is the only required method in any component class. This method should not modify the component state; it should just display the result of the component it invoked. The render() method should also examine this.state and this.props. Use the other life cycle methods to interact with the browser. In other words, render is for viewing purposes only.



4. What is JSX? What is one notable difference between HTML and JSX?

  Your answer: JSX is the script style used in React. In other words, the JavaScript language formatted for React. A notable difference between HTML and JSX is that understandings in React when creating classes and divisions (therefore, less keystrokes to make things like a table, paragraphs, etc).

  Researched answer: JavaScript Syntax Extension (JSX) also known as JavaScript XML is some syntactical sugar for React. Developers can place HTML right into JavaScript using JSX. However, one notable difference between JSX and HTML is defining inline styles. Styles within JSX are written as an object with its properties in camelCase and its values in quotations. After that structure is set, you can then pass the object inline. HTML gives more freedom to define as many objects as desired within the opening tag. The value of each object will be in quotations. though this endless structure is available in HTML, it is recommended to keep the list at a minimal to maintain the visibility of the website through search engines. Can't make much of a profit if no one can find your webpage.



5. What is yarn? What file(s) are modified in a React application when you run yarn?

  Your answer: `yarn` is a function within git that allows for certain applications like Jest and React to download dependencies. These dependencies (software/supportive applications) allow Jest and React to pull up projects, open browsers, or perform unit tests.

  Researched answer: Looking for an independent open-source project manager? Then check out yarn. The yarn platform allows you to create a repository that can take on several sub components. It also allows other developers to provide solutions to various problems. Just a giant box of collaboration. Certain yarn commands are very useful with React, such as $ yarn create react-app creates a directory and installs all the necessary files and dependencies. $ yarn start will open a browser for the current project and allow the terminal to be a temporary server. Yarn is certainly a thread to secure an efficient, cohesive working foundation.



6. STRETCH: What is an anonymous function in JavaScript?

  Your answer: Anonymous functions in JavaScript allow certain behaviors to occurs to objects in a class. In actually, the functions are classes with that produce a builtin behavior for the code block.

  Researched answer: For a creative soul like myself, anonymous functions give me a break from naming a function. Thank you, anonymous functions for being functions without names. They can be passed as arguments to other functions. They can also be immediately invoked. The basic structure of an anonymous function is as follows:

  (function() {console.log('Need to learn this technique!');})();

  The function expression with trailing parentheses allowing you to invoke the function. Variables need to be assigned to call upon the function later. Of course, it can be shortened using arrow function:

  let brain = function () {console.log('Need to learn this technique!');}; is the same as
  let brain = () => console.log('Need to learn this technique!');

  let multiply = function (w, e) {return w + e;}; is equivalent to
  let add = (w, e)  => w + e;
  
## Looking Ahead: Terms for Next Week

1. Conditional rendering: React way of toggling between the true or false of conditional operators on the UI

2. Props: communicate by passing data and methods between components (even nested components)

3. JavaScript Events: JavaScript coded responses to HTML events that occur when a user or browser manipulates a page

4. Object oriented programming: encapsulation, abstraction, inheritance, and polymorphism

5. Ruby: "language of careful balance", very flexible programming language
