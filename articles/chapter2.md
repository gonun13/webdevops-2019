# CSS

This is where you go to put a nice skin over your skeleton (HTML). CSS is very extensive and allows you to style the elements of your HTML using selectors. It can get very messy really quickly, so some care is required in organizing all the styling. But just like HTML, it's a must know for any web developer.

## Why use?

This is the second cornerstone of the web and there is also no way to avoid it. It took awhile for this standard to dug in and you should master it's basic concepts like cascading, positioning and browser support. 

## Our project

So, let's add a folder to hold our stylesheets...

![folders](https://github.com/gonun13/webdevops-2019/blob/master/src/chapter2/article/dirs1.png)

And this will be our main.css
```code
body {
    width: 100%;
    height: 100%;
    background-color: #2f3238;
    margin: 0;
    padding: 0;
}
.container {
    display: flex;
    align-items: center;
}
#logo {
    max-width: 20%;
}
nav {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color: #969799;
    width: 100%;
}
nav ul {
    display: flex;
    list-style: none;
    align-items:center;
}
nav li {
    font-size: 1.2rem;
    margin-left: auto;
    margin-right: auto;
}
#photos {
    display: flex;
    align-items:center;
}
#photos img {
    max-width:33.33%;
}
```
As you can see, we identify some of the elements of our HTML template and apply some style to them. Pretty straightforward. And here is the outcome...

![screenshot](https://github.com/gonun13/webdevops-2019/blob/master/src/chapter2/article/shot1.png)

Ahhhh, much better! But is the work of a web designer over yet? Not quite...
If we open on a mobile device this is what we will see...

![screenshot](https://github.com/gonun13/webdevops-2019/blob/master/src/chapter2/article/shot2.png)

Yeah, we're not quite there. We need to improve our stack a bit more.

## Issues
- *"Hey, this doesn't look the same on my browser/resolution/device!"*

Welcome to the biggest issue of web design... since ever.
To ensure a consistent look and feel while also giving us a jumpstart, we need a [CSS Framework](chapter3.md)

- *"Don't we also need a CSS Preprocessor like LESS, SASS or Stylus?"*

No. It's an extra overhead for a project, with minimal gains. There are other smart ways to achieve similar results without learning extra syntax. The only valid point to waste your time on something like this it's if you're a theme designer or building [CSS Frameworks](chapter3.md)

- *"Your menu still doesn't do anything..."*

True. We will tackle that on [Chapter 4 - Javascript](chapter4.md)

### webdevops
[Intro](../README.md)

[Chapter 1 - HTML](chapter1.md) 

[Chapter 3 - CSS Frameworks](chapter3.md) 
