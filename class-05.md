# `HTML`

| Number       | Topic                       |
| -----------  | --------------------------- |
| 1            | HTML Image tag with Example |
| 2            | HTML Colors                 |
| 3            | HTML Text Formatting        |

<hr>

# HTML Image tag with Example

> web is not just about text, its multi-media and HTML's multimedia features allow you to <br>
> include images, audio clips, video clips, and other. `<img>` element, used to embed a simple image in a webpage. <br>
> Images can improve the design and the appearance of a web page.


> ***Syntax:***

![](https://www.html-5-tutorial.com/images/a-tag.gif)


> **Example**
``` ruby 
<!DOCTYPE html>
<html>
 <body>
    <img src="https://www.html-5-tutorial.com/images/a-tag.gif" alt="Pic is not allowed">
 </body>
</html>
```

***Image Size - Width and Height:***
``` ruby 
<!DOCTYPE html>
<html>
<body>
    <img src="https://www.html-5-tutorial.com/images/a-tag.gif" alt="Sun Rise" width="400px" height="450px">
</body>
</html>
```
<hr>


# HTML Colors

![](https://i.stack.imgur.com/KEKiw.gif)

> ***Background Color***
> **Example..**

``` ruby
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```


> ***Text Color***
> **Example ..**

``` ruby
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

> ***Border Color***
> **Example..**
``` ruby
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

<hr>

> ***HTML Text Formatting***
> **HTML `<b>` and `<strong>` Elements**
> The HTML `<b>` element defines bold text, without any extra importance.

``` ruby
<b>This text is bold</b>
```

> The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.

``` ruby
<strong>This text is important!</strong>
```


> **HTML `<i>` and `<em>` Elements**
> The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.
> Tip: The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
 
``` ruby
 <i>This text is italic</i>
```
> The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.
> Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress. 
 
``` ruby
<em>This text is emphasized</em>
```

> ***Definition and Usage***
> The font-family property specifies the font for an element.
>
> The font-family property can hold several font names as a "fallback" system. If the browser does not support the first font, it tries the next font.
>
> There are two types of font family names:
>
> - family-name - The name of a font-family, like "times", "courier", "arial", etc.
> - generic-family - The name of a generic-family, like "serif", "sans-serif", "cursive", "fantasy", "monospace".

> **Example..**

> Specify the font for two paragraphs:
``` ruby
p.a {
  font-family: "Times New Roman", Times, serif;
}

p.b {
  font-family: Arial, Helvetica, sans-serif;
}

```

***CSS text-shadow Property***

> The text-shadow property adds shadow to text.
>
> This property accepts a comma-separated list of shadows to be applied to the text.

***Examples : ***

``` ruby
h1 {
  text-shadow: 2px 2px 8px #FF0000;
}
```

``` ruby
h1 {
  color: white;
  text-shadow: 2px 2px 4px #000000;
}
```

``` ruby
h1 {
  text-shadow: 0 0 3px #FF0000;
}
```

``` ruby
h1 {
  text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;
}
```









