# Welcome to the first lesson!

## Getting Started

### Getting the right tools

First, before you write any code,
you make sure that you have
checked off all of these steps:

- You must have IDE ( Integrated Development Environment ), which is also used as a text editor, I suggest using [VSCode](https://code.visualstudio.com/).
- Something that you must also have a modern browser, I suggest [Chrome](https://chrome.google.com).

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

#### Variables

Lets look at variables.
This is going to be how
you would create a variable.

This declaration creates
a new variable called
myVariable,
and is assigned with the
value of the number 1234.

```javascript
let myVariable = 1234;
```

#### The console

Now you will learn how to log
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
console.log(helloWorld);

helloWorld = 'Leiloukou is best!';
console.log(helloWorld);
```

The first console.log(),
should log:

```javascript
'Hello, world!';
```

And then the second one
should log:

```javascript
'Leiloukou is best!';
```

#### Back to variables

Next, you will create a constant variable,
AKA, a variable that cannot change.

```javascript
const myVariable = 'This variable cannot change...';
```

To prove a point,
this is what the
console would output,
if you tried to change
a constant variable.

The code:

```javascript
const myVariable = 'This variable cannot change...';
console.log(myVariable);

myVariable = 'This is not supposed to change';
console.log(myVariable);
```

The console output:

```error
VM38:4 Uncaught TypeError: Assignment to constant variable.
    at <anonymous>:4:12
```

Here is a tip,
always read the
error message,
don't just try
to find it yourself.

#### Comments

Comments are line of
text that do not get run.
A single-line comment
is written like this:

```javascript
// This is just a code comment.
```

Comments are used to describe code,
I sometimes forget why I chose to
write my code in a specific way,
I just read what my comment says.

Here is an example:

```javascript
// This logs "Hello, world!" to the console.
console.log('Hello, world');

// This creates a variable.
let leil = 'Cool-var';
```
