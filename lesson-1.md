# Welcome to the first lesson!<br />

## Getting Started<br />

### Getting the right tools<br />

First, before you write any code,<br />
you make sure that you have<br />
checked off all of these steps:<br />
<br />
[ ] You must have IDE ( Integrated Development Environment ),<br />
which is also used as a text editor,<br />
I suggest using [VSCode](https://code.visualstudio.com/).<br />
[ ] Something that you must also have a modern browser,<br />
I suggest [Chrome](https://chrome.google.com).<br />
<br />
### The mindset<br />
<br />
When you learn a new scripting language,<br />
or even a new programming language,<br />
you have to have the right mindset.<br />
In Javascript, you have to think about<br />
everything as functions, or objects.<br />
Very far and much later on in the course,<br />
we will learn about something called classes.<br />
<br />
But lets not get ahead of ourselfs,<br />
lets get onto the actual code.<br />
<br />
### The first code<br />
<br />
Lets look at variables.<br />
This is going to be how<br />
you would create a variable.<br />
<br />
This declaration creates a new variable called myVariable,<br />
and is assigned with the value of the number 1234.<br />
<br />
```javascript
let myVariable = 1234;
```
<br />
Now you will lear how to log<br />
something to the console.<br />
<br />
First you will have to get a<br />
way to view something to the console.<br />
Here is the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for
VSCode.<br />
<br />
Once you have that installed<br />
go to the port that it is on,<br />
and press ctrl + shift + i,<br />
or cmd + option + i, on mac,<br />
the go to the console,<br />
it will show you what you<br />
log to the console.<br />
<br />
```javascript
console.log('Hello, world!');
```
<br />
As we all know,<br />
one thing can mean something<br />
in human speak, so it doesn't<br />
surprise me that, in Javascript,<br />
you can do the same thing.<br />
But only with the let keyword.<br />
<br />
```javascript
let helloWorld = 'Hello, world!';
console.log(helloWorld);

helloWorld = 'Leiloukou is best!';
console.log(helloWorld);
```
<br />
The first console.log(),<br />
should
Next, you will create a constant variable,<br />
AKA, a variable that cannot change.<br />
<br />
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