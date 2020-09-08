# What is HTML Links

> The HTML `<a>` tag defines a hyperlink. It has the following syntax:
> `<a href="url">link text</a>`
> The most important attribute of the <a> element is the href attribute, which indicates the link's destination.
> The link text is the part that will be visible to the reader.
> Clicking on the link text, will send the reader to the specified URL address.




***By default, links will appear as follows in all browsers:***

> An unvisited link is underlined and blue
> A visited link is underlined and purple
> An active link is underlined and red



# HTML Links - Use an Image as a Link

> To use an image as a link, just put the <img> tag inside the <a> tag:

Example
``` java
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```


# Link to an Email Address

``` java
<a href="mailto:someone@example.com">Send email</a>

```


# Link Titles
> The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

``` java
<a href="https://www.dana.com/html/" title="Go to HTML section">  Visit our HTML Tutorial  </a>

```

# More on Absolute URLs and Relative URLs
``` java
<a href="https://www.dana.com/html/default.html"> HTML tutorial</a>
```

<hr>

> Use the <a> element to define a link
> Use the href attribute to define the link address
> Use the <img> element (inside <a>) to use an image as a link
> Use the mailto: scheme inside the href attribute to create a link that opens the user's email program

<hr>

# HTML Layout Elements

![](https://www.w3schools.com/html/img_sem_elements.gif)

> HTML has several semantic elements that define the different parts of a web page:

***HTML5 Semantic Elements***
- <header> - Defines a header for a document or a section
- <nav> - Defines a set of navigation links
- <section> - Defines a section in a document
- <article> - Defines an independent, self-contained content
- <aside> - Defines content aside from the content (like a sidebar)
- <footer> - Defines a footer for a document or a section
- <details> - Defines additional details that the user can open and close on demand
- <summary> - Defines a heading for the `<details>` element
> You can read more about semantic elements in our HTML Semantics chapter.


***HTML Layout Techniques***
> There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:
- CSS framework
- CSS float property
- CSS flexbox
- CSS grid






# Controlling the Position of Elements

> CSS has the following positioning schemes that allow you to control <br>
> the layout of a page: normal flow, relative positioning, and absolute <br>
> positioning. You specify the positioning scheme using the position <br>
> property in CSS. You can also float elements using the float property. <br>


![](https://miro.medium.com/max/1200/1*eQ1bD3AL6BXU6-dszAxd1g.png)


![](https://i.pinimg.com/originals/bd/bf/6c/bdbf6c0b0788d019e0c11e42b7225c5f.png)


<hr>

# What is JS Function 

> Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is
> similar to a procedure—a set of statements that performs a task or calculates a > value, but for a 
> procedure to qualify as a function, it should take some input and return an output where there is some
> obvious relationship between the input and the output. > To use a function, you must define it somewhere 
> in the scope from which you wish to call it.


> A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

- The name of the function.
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, {...}.


***For example,*** the following code defines a simple function named square:
``` java
function square(number) {
  return number * number;
}
```

# What is Calling functions

> Defining a function does not execute it. Defining it simply names the function and specifies what to do when the function is called.

> 'Calling' the function actually performs the specified actions with the indicated parameters. For example, <br>
> if you define the function square, you could call it as follows:

``` java
square(5);
```

> The preceding statement calls the function with an argument of 5. The function executes its statements and returns the value 25.
> Functions must be in scope when they are called, but the function declaration can be hoisted (appear below the call in the code), as in this example:


<hr>











































