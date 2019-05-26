# Presentation-TypeScript
Hi, my name is Gutsev Stas and I would like to tell about TYPESCRIPT.

`(Slide - TYPESCRIPT)`

**What is TYPESCRIPT?**

`(Slide - What is TYPESCRIPT)`

TypeScript is an open-source programming language developed and maintained by Microsoft.  It was created to allow for optional static type checking, which would be particularly useful when developing large scale applications. 
TypeScript is a superset of JavaScript, meaning that it contains all of the functionality of JavaScript and then some. Therefore, any program written in valid JavaScript will also run as expected in TypeScript.  In fact, TypeScript compiles simply to plain JavaScript.  TypeScript offers us more control over our code via type annotations, interfaces, and classes.

`(Slide - TYPESCRIPT features)`

Typescript can be explained as a superset of Javascript. It means that every Javascript (also ES6 & newer versions) code is valid Typescript code, but Typescript comes with some additional features:
* Strong-typed variables
* Object-oriented programming

`(Slide - INSTALLING TYPESCRIPT)`

**INSTALLING TYPESCRIPT**

Before we can use Typescript, we need to install it on our computer. There are two main ways to get the TypeScript tools:
* Via npm (the Node.js package manager);
This command will install Typescript globally so you can use it in any project. After the installation completed, you can verify it 
* By installing TypeScript’s Visual Studio plugins.

`(Slide - translates Typescript)`

Typescript files have a .ts extension.
Browsers don’t understand Typescript code, so later it needs to get translated to Javascript.

`tsc yourFileName.ts`

This command creates a Javascript file automatically and translates your Typescript code JS.

`(Slide - STRONG TYPING)`

**STRONG TYPING**

JavaScript is dynamically typed. Therefore, programs written in JavaScript do not know the data type of a variable until that variable is assigned a value at runtime. The variable can be reassigned or coerced into a value of a different type with no issues or warning. This can result in bugs that are often overlooked, especially in large applications.
TypeScript, on the other hand, uses static typing. Variables can be given a type when they are declared. TypeScript will check types at compile time, and throw an error if the variable is ever given a value of a different type. However, the error does not prevent the code from executing. The code will still be compiled into plain JavaScript and run normally. In this way, TypeScript is kind of like a “spellcheck” for your code. It will let you know when something looks off, but it won’t change how your code runs.
Static typing is optional in TypeScript. Variables can be given the type any, which will allow its values to be any type. If no type is given, the type will be set to any by default.

`(Slide - CLASS)`

**CLASS**

Another important feature of TS is that we can write object-oriented code. For example, we can define classes and interfaces:
It wasn’t until the introduction of ECMAScript2015, or ES6, that JavaScript introduced classes to the language. However, it is important to note that these classes do not change the language’s prototype-based inheritance.
TypeScript allowed for the ability to use classes before they were officially implemented in ES6. TypeScript allows the developer to extend existing classes to construct new ones using inheritance.

`(Slide - CONSTRUCTORS)`

**CONSTRUCTORS**

In Object-Oriented Programming, we have an important method called constructor(). Every class has actually a default constructor method, and it is called when we create an instance of that class:
The question mark makes the parameters optional.
`(Slide - ACCESS MODIFIERS)`

**ACCESS MODIFIERS**

In Object-Oriented Programming, access modifiers are being used for restricting or allowing to access the variables of a class from outside. There are 3 types of access modifiers:
* Public — Allows access from outside of a class
* Private — Doesn’t allow access from outside of a class
* Protected — Allows access only within a class and its derived classes
All members of a class are Public by default.
So we can (and should) restrict access from outside by adding the privatekeyword to a class’s members.

`(Slide - WHAT ELSE CAN TYPESCRIPT DO)`

**WHAT ELSE CAN TYPESCRIPT DO?**

In addition to displaying the errors at compile time, certain IDEs such as Visual Studio Code will present the errors to the developer while they are typing the code. This makes correcting simple careless errors much quicker and easier.
TypeScript can also infer types that aren’t explicitly declared by the developer, such as inferring the return value type of a function. If the function is adding two parameters that were declared as both number, TypeScript will infer the return value must be of type number.

`(Slide - PROS & CONS)`

`(Slide - PROS)`

**TYPESCRIPT PROS**

Here are the strong points of TypeScript:
* Rich IDE support with autocomplete and code navigation features
* Safe automatic refactorings
* Discoverable APIs and more self-explanatory code contracts (through type declarations)
* Typos caught at compilation time
* Class-based OO, with inheritance, private members and interfaces
* Module support
* Existing JavaScript code interoperability:
* Compiles down to idiomatic JavaScript
* Any JavaScript code is a valid TypeScript code

`(Slide - CONS)`

**TYPESCRIPT CONS**

However, everything comes at a price, and TypeScript is no exception. Here are some things that could be considered drawbacks or hurdles compared to JavaScript:
* In order to get the most out of the TypeScript, developers will need to use the type annotations everywhere in their code, which might at times be cumbersome (or perceived as such coming from a dynamic language background). Some effort might be required to write a strongly-typed version of the JavaScript code.
* Not all third-party libraries have ambient definitions available. The development team will have to write and maintain their own if they want to use a particular library and take advantage of TypeScript.
* In order to run the application in the browser, a compile step is required to transform TypeScript into JavaScript.
