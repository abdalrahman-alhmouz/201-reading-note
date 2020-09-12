# JS Object Literals; The DOM
<hr>

# The people say : That Understanding The Problem Domain Is The Hardest Part Of Programming..!!
> Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one,
> that has a very similar pattern repeated on it and is double-sided?
> The same thing happens when writing code.  Writing code is a lot like putting together a jigsaw puzzle.  We put together > code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

## Is this right ?!

*Lets see..*

<hr>

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

> The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an XML or HTML
> document as a tree structure where in each node is an object representing a part of the document. The DOM represents a 
> document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow
> programmatic access to the tree; with them one can change the structure, style or content of a document. Nodes can have event handlers attached to them. Once an event is triggered, the event handlers get executed.

# WORKING WITH THE DOM TREE

> ***Accessing and updating the DOM tree involves two steps:***
> 1: Locate the node that represents the element you want to work with.
> 2: Use its text content, child elements, and attributes.
> STEP 1: ACCESS THE ELEMENTS
> STEP 2: WORK WITH THOSE ELEMENTS


```
The terms elements and element nodes are used interchangeably
but when people say the DOM is working with an element,
it is actually working with a node that represents that element.
```

# TRAVERSING THE DOM

> When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.


> ***parentNode***
> This property finds the element
> node for the containing (or
> parent) element in the HTML.
> (1) If you started with the
> first `<l i >`element, then its
> parent node would be the one
> representing the `<ul >`element.
  
  
  
> ***previousSibling/nextSibling***
> These properties find the
> previous or next sibling of a node
> if there are siblings.
> If you started with the first `<1 i >`
> element, it would not have a
> previous sibling. However, its next
> sibling (2) would be the node
> representing the second `<l i >`.


> ***firstChild/lastChild***
> These properties find the first or
> last child of the current element.
> If you started with the `<u 1 >`
> element, the first child would be
> the node representing the first
> `<l i>` element, and (3) the last
> child would be the last `<1 i >`.


![](https://res.cloudinary.com/practicaldev/image/fetch/s--3PePIjz5--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/qnbqubcipqjl5pb3i8ds.gif)

















