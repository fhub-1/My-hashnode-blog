## 6 essential skills for React web developers

React is the ultimate library for front-end developers today. Simply put, you get better at development when you learn React, and many organizations view these skills as essential. React developers should be hungry to level-up or audit the skills essential to Facebook’s prominent JavaScript Library.

See how you stack up with these 6 essential skills for React developers.

1. HTML + CSS
No front-end dev is a stranger to HTML and CSS. The ability to work with and craft user interfaces is necessary to every organization. At a high level, React developers should be able to:

Work with and write semantic HTML tags
Work with and write CSS selectors
Implement a CSS reset
Understand the box model and how to reset to border-box
Understand flexbox
Work with and implement responsive web principles including the proper user of media queries
2. JSX
In React, you never really touch HTML proper. You work with a syntax extension that is truly one of the most remarkable parts of the React ecosystem: JSX. JSX looks so much like HTML you may think of it as HTML-flavored JavaScript. What’s cool about JSX is that if you know HTML and CSS, you intuitively know how to work with JSX.

JSX is an abstraction on top of the React.createElement() API. One reason it is vital to the library—and why the React team chose to go with it in the first place—is that the API would be too cumbersome to use in terms of scaling. One potentially could use React.createElement() to build out an entire application, however this wouldn’t be any more efficient than just using HTML proper. It may feel at first that we’ve taken a step backward by adding our Markup into our template logic, however a few quick minutes with JSX and you’ll be hooked on the style.

JavaScript Fundamentals + ES6 You can’t rock React without a firm understanding of the fundamental concepts that the JavaScript language provides, but these ES6 skills are also essential:
Variables and scoping

Understanding when and where you have access to the data you need is critical. Variables are the mechanism built into JavaScript that allow us to hold onto data in memory and access that data later on within our applications.

ES6 brought with it new keywords that we can use to store variables other than the traditional var keyword (like let and const). You may choose to live by the principle that unless you absolutely need var, use const until your linter tells you otherwise, then default to let.

Arrays and objects

React suggests a pattern that your view is a function of your state. Arithmetically put, that’s v = f(s), and something you need to remember as you revisit your skills in the foundations of the library.

State is data that we want to show to users or items in memory that we can access in order to allow our users to interact with our data. We hold all of the data that we present on an object called state and access these bits of data via properties on this state object. This is how React received its name; when state changes, the view updates (v = f(s);). So your view ‘reacts’ to the changes that are made in your state object.

You should brush up on how to mutate objects and change values of properties on them. Don’t worry, React takes care of the mechanism through a nifty function called setState() to make this work to your advantage.

Array methods

It’s one thing to be able to store data and access it within arrays and objects. It’s another to be able to manipulate that data properly. The built-in JavaScript array methods are essential tools in every developer’s toolbox. Focus in on .map, .filter and .reduce for maximum impact.

Functions and arrow functions

In React, every single component you build is a function in one way or another. Remember that ‘classes’ are just constructor functions under the hood. Regardless of the syntax you’re using, when building functional components or class components you’re using some form of a function.

Don’t underestimate the importance of these fundamentals. Many practices out there today that lend themselves to functional programming. The chance to use JavaScript functions to build out small chunks of UI is like building a Lego set without instructions. Each piece of UI is an encapsulated function that contains the state data your elements need to present, the elements themselves and the formal component logic you need to use that logic. Each component is a Lego brick, and it’s up to you to fit them all together.

DOM Manipulation and event handlers

In React, manipulating the actual DOM elements is rare. Remember we now have the JSX abstraction at our disposal. The native event object that you get with normal DOM manipulation in React is actually wrapped up in what’s called the SyntheticEvent. Make sure you can attach different types of events to HTML elements such as onclicks, onchange, mouseenter, etc.

The “this” keyword

The ‘this’ keyword is one of the commonly misused features in JavaScript. Think of ‘this’ as a pointer to an object. For example, you can use the ‘this’ keyword to reference an object without having to refer to that object’s name.

Higher order functions and callback functions

The idea that functions can be passed around as arguments—in the case of high order functions and callbacks—is what drives the input/output model of functional programming.

You pass handlers around everywhere in React. Most of the time the handlers you pass around are in the form of methods that are chained onto an object and accessed as properties, which will be bound up in the prototype chain. However, there are moments that you need to reach outside of the React component paradigm or create a few different types of components that extend some of the functionality to one another. These patterns are commonly referred to as advanced React patterns and they’re finding their way into the better/common practices realm. React will push you to be innovative and creative as you scale along with it.

Prototypal inheritance and object creation

React lends itself to a functional programming paradigm in many aspects. However, you work in the world of classes and, as a result, a world of object creation. If you understand the basics of how the prototype chain works in JavaScript, you’ll know what you need to about how we achieve inheritance in JavaScript. Remember, that there are no traditional classes in JavaScript. The class keyword is just syntactic sugar on top of the object prototype chain in JavaScript.

The ‘class’ keyword

JavaScript classes aren’t the same as classes in a traditional programming sense. You create classes that encapsulate your template logic, formal JavaScript logic and even styles known as components. These components are the building blocks of any React application, and there are only two ways to write the basic component: either by declaring it as a function or declaring it as a class.

Assess your proficiency with classes by making sure you can answer:

How do I set up methods on a class?
How do I bind those methods together?
How do I access properties that are found on the constructor?
How do I create objects that would be considered ‘children’ of parent objects?

Git Git is essential to every developer's toolkit for storing projects on solutions like GitHub, Bitbucket and GitLab. Skills that should just be part of your day-to-day include:
Tracking changes with add, commit, push and pull
Branching and merging strategies
Handling merge conflicts
5. Node + npm
Node may be a surprise to many. Why would you need to know how to work with Node in order to be a client-side React dev? While you can pull React into any HTML file, there will be many other packages out there that will allow you to extend the React library.

React developers need to have a solid understanding of the npm registry. This is the place where software developers can go to get software to help them build software. Sounds funny, but truly that’s all the npm is: a cloud storage for packages we call dependencies.

Yarn vs npm

Yarn is a package manager that is built to utilize the npm registry. Yarn actually optimizes your npm workflows. Yarn and npm somewhat compete today, but the mission of Yarn has been to solve a lot of the problems that are accepted in the Node/npm ecosystem. npm has been doing everything it can to follow the patterns and practices that Yarn presents.

6. Redux
Hot button issue alert: React has built-in state management. And many devs have been burned along the way by discovering the asynchronicity of state updates and how React handles them. For that reason, and for scalability, Redux was born. Redux is a state management library and more. It’s not a framework, but an opinionated way of working with data. The principles behind Redux are along the lines of functional programming and immutability, but it’s not a one-size-fits-all-solution. Mastering the concepts of fundamental React programming prior to diving into Redux is key.

To learn more about the various skills to learn to be a successful web developer check out our My [YoutubeChannel](https://bit.ly/3ot3X28)web development.