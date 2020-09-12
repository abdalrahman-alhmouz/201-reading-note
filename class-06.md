# JS Object Literals; The DOM
<hr>

# The people say : That Understanding The Problem Domain Is The Hardest Part Of Programming..!!
## Is this right ?!
*Lets see..*



## WHAT IS AN OBJECT?
> Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life. 
> The concept of objects in JavaScript can be understood with real life, tangible objects.

> In JavaScript, an object is a standalone entity, with properties and type.
> Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

`objectName.propertyName`

***Example:***

``` ruby
var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
```

> The `this` Keyword
> In a function definition, this refers to the "owner" of the function.
>
> In the example above, `this` is the ***person object*** that "owns" the ***fullName*** function.
>
> In other words,***this.firstName*** means the ***firstName*** property of this object.
>
> Read more about the `this` keyword at JS this Keyword.

## Using Built-In Methods

> This example uses the `toUpperCase()` method of the String object, to convert a text to uppercase:

``` ruby
var message = "Hello world!";
var x = message.toUpperCase();
```
? The value of x, after execution of the code above will be:

``` ruby
HELLO WORLD!
```

## Adding a Method to an Object

***Example:***
``` ruby
person.name = function () {
  return this.firstName + " " + this.lastName;
};
```
<hr> 

# Document Object Model

![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/330px-DOM-model.svg.png)

> The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an XML or HTML document as a tree structure where in each node is an object representing a part of the document. The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree; with them one can change the structure, style or content of a document. Nodes can have event handlers attached to them. Once an event is triggered, the event handlers get executed.



![](https://res.cloudinary.com/practicaldev/image/fetch/s--3PePIjz5--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/qnbqubcipqjl5pb3i8ds.gif)

















