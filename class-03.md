# HTML 

<hr>
<br>

#  `HTML lists` ..

![](https://miro.medium.com/max/876/1*HjpS84zsYK2ud3Ale19Oqw.png)

 <hr>
 <br>
 
> ***Unordered HTML List*** <br>
> An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag. <br>
> The list items will be marked with bullets `(small black circles)` by default:
  
  ``` ruby
  <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
  ```
  
  <br>
  
  
> ***Ordered HTML List*** <br>
> An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag. <br>
> The list items will be marked with numbers by default:

``` ruby 
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

<hr>
<br>


# HTML List Tags


| Tag  | Description                |
| ---- | ------------------------   |
| ul   | Defines an unordered list  |
| ol   | Defines an ordered list    |
| li   | Defines a list item        |


<hr>

![](https://i.gifer.com/4ltg.gif)

<hr>

<br>



# `HTML boxes`

![](https://i0.wp.com/css-tricks.com/wp-content/uploads/2017/10/gif4.gif?ssl=1)


# Margin and padding

![](https://res.cloudinary.com/practicaldev/image/fetch/s--IdKeqjVS--/c_imagga_scale,f_auto,fl_progressive,h_1080,q_66,w_1080/https://thepracticaldev.s3.amazonaws.com/i/bte89ts228bjy8j1vv4e.gif)

***Explanation of the different parts:***

> - Content - The content of the box, where text and images appear
> - Padding - Clears an area around the content. The padding is transparent
> - Border - A border that goes around the padding and content
> - Margin - Clears an area outside the border. The margin is transparent

***Example***
``` ruby
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

<br>
<hr>

# javascript data types..

![](https://i.pinimg.com/originals/66/8d/fc/668dfc002312ab58e0d1cb15e0b98a5e.png)

> There are six basic data types in JavaScript which can be divided into three main categories: primitive <br>
> (or primary), composite (or reference), and special data types. String, Number, and Boolean are primitive data types. <br>
> Object, Array, and Function (which are all types of objects) are composite data types.

> ***The string data type***
> is used to represent textual data (i.e. sequences of characters).<br>
> Strings are created using single or double quotes surrounding one or more characters, as shown below:


``` ruby 
var a = 'Hi there!';  // using single quotes
var b = "Hi there!";  // using double quotes
```

``` ruby
var a = "Let's have a cup of coffee."; // single quote inside double quotes
var b = 'He said "Hello" and left.';  // double quotes inside single quotes
var c = 'We\'ll never give up.';     // escaping single quote with backslash
```
> ***The Number Data Type***
> The number data type is used to represent positive or negative numbers with or without decimal place, <br>
> or numbers written using exponential notation e.g. 1.5e-4 (equivalent to 1.5x10-4).

``` ruby 
var a = 25;         // integer
var b = 80.5;       // floating-point number
var c = 4.25e+6;    // exponential notation, same as 4.25e6 or 4250000
var d = 4.25e-6;    // exponential notation, same as 0.00000425
```

> ***The Boolean Data Type***
> The Boolean data type can hold only two values: true or false. <br>
> It is typically used to store values like yes (true) or no (false), on (true) or off (false), etc. as demonstrated below:

```ruby 
var isReading = true;   // yes, I'm reading
var isSleeping = false; // no, I'm not sleeping
```

<hr>
<br>

# JavaScript if else and else if..

![](https://images.code.org/d873962609e99f821249fde2007ca1bb-image-1479494721725.gif)


> *Very often when you write code, you want to perform different actions for different decisions.*
>
> *You can use conditional statements in your code to do this.*
>
> *In JavaScript we have the following conditional statements:*

- Use if to specify a block of code to be executed, if a specified condition is true
- Use else to specify a block of code to be executed, if the same condition is false
- Use else if to specify a new condition to test, if the first condition is false
- Use switch to specify many alternative blocks of code to be executed



``` ruby
if (hour < 18) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```

<hr>


![](https://user-images.githubusercontent.com/9205389/28846831-c063158c-76c1-11e7-8f6c-ae9fb458845b.gif)



<hr>










