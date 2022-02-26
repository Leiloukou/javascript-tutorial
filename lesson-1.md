# Welcome to the first lesson!

## Getting Started

### Getting the right tools

First, before you write any code,
you make sure that you have
checked off all of these steps:

[ ] You must have IDE ( Integrated Development Environment ),
which is also used as a text editor,
I suggest using [VSCode](https://code.visualstudio.com/).
[ ] Something that you must also have a modern browser,
I suggest [Chrome](https://chrome.google.com).

### The mindset

When you learn a new scripting language,
or even a new programming language,
you have to have the right mindset.
In Javascript, you have to think about
everything as functions, or objects.
Very far and much later on in the course,
we will learn about something called classes.

But lets not get ahead of ourselfs,
lets get onto the actual code.

### The first code

Lets look at variables.
This is going to be how
you would create a variable.

This declaration creates a new variable called myVariable,
and is assigned with the value of the number 1234.

```javascript
let myVariable = 1234;
```

Now you will lear how to log
something to the console.

First you will have to get a
way to view something to the console.
Here is the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for
VSCode.

Once you have that installed
go to the port that it is on,
and press ctrl + shift + i,
or cmd + option + i, on mac,
the go to the console,
it will show you what you
log to the console.

```javascript
console.log('Hello, world!');
```

As we all know,
one thing can mean something
in human speak, so it doesn't
surprise me that, in Javascript,
you can do the same thing.
But only with the let keyword.

```javascript
let helloWorld = 'Hello, world!';
console.log(helloWorld);V
helloWorld = 'Leiloukou is best!';
console.log(helloWorld);
```

The first console.log(),
should
Next, you will create a constant variable,
AKA, a variable that cannot change.

```javascript
// This declaration creates a new variable called myVariable,
// as a new String datatype, with the value of Lil' Wuth Who Goeth Leil.
// Also, notice the backslash character, used to escape normal single-quote syntax,
// which allows us to create an apostrophe.
// Also note the use of the const keyword, which creates a constant variable,
// of which you cannot redefine, now, this may seem like a bad idea, I mean,
// not being able to change a variable, defeats the whole purpose of variables in general,
// so what is the point?
// Sometimes you might want to create a variable that doesn't change.
// Also, in ES6, also know as Ecma Script 2015,
// and Node.js, which is a backend Javascript language, you can import modules,
// if you would like to learn how to import modules, you can skip a few hundred lessons.
const myVariable = new String('Lil\' Wuth Who Goeth Leil');

// This logs the variable to the console
window.console.log(window.myVariable);
```