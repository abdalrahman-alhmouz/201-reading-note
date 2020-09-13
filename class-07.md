# Domain Modeling
> HTML DOM methods are actions you can perform (on HTML Elements).
>
> HTML DOM properties are values (of HTML Elements) that you can set or change.




***The following example changes the content (the innerHTML) of the <p> element with id="demo":***

*Example :*

``` ruby
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
```

***In the example above, getElementById is a method, while innerHTML is a property.***


# Model epic fails videos
> Imagine you've been tasked to build a program that models the popularity of epic fail videos. 

# Using Math.random() in JavaScript

***In JavaScript, to get a random number between 0 and 1, use the `Math.random()` function.***

``` ruby
console.log(Math.random())
0.5408145050563944
```

***If you want a random number between 1 and 10, multiply the results of `Math.random` by 10, then round up or down.***
*Use `.floor` to round down to a whole number:*
``` ruby
console.log(Math.floor(Math.random() * 10))
```

*Use `.ceil` to round up to a whole number:*
``` ruby
console.log(Math.ceil(Math.random() * 10))
```

*Use `.round` to round to the nearest whole number:*
``` ruby
console.log(Math.round(Math.random() * 10))
```










