# HTML

This is the skeleton of any web app. HTML builds the DOM (Document Object Model) that browsers use to show you the content and all the interaction. There are many ways to build, manipulate or abstract HTML but in the end, every webdev should have mastery of HTML or at least know all the basic building blocks. And the most important HTML is simple!

# Why?
Everything has a start and this was it. It's one of the cornerstones of the web and the formatting standard needed to start the revolution. With so many modern frameworks going around that offer alternative starts to web development, you might be tempted to skip on it. But don't. Begginers should start with HTML and everyone else should try to keep it in their stacks, in one way or the other.  It's a good placeholder at the beggining of every project and for me, still the best templating base for documents.

# Our project

So let's us start with our photography app. I'll need a menu and someway to display the photos.
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Gonun13 Photography</title>
  </head>
  <body>
    <nav>
      <ul>
        <li>Home</li>
        <li>About</li>
        <li>Models</li>
        <li>Landscapes</li>
        <li>Life</li>
        <li>Contact</li>
      </ul>
    </nav>
    <div id="photos">
       <img src="">
       <img src="">
       <img src="">
    </div>
  </body>
</html>
```

# Problems
Depending on your experience level, you'll see some issues right away. But let's start with the obvious ones.
- *"This looks horrible!"*

True! This is why we need [Chapter 2 - CSS](chapter2.md)
- *"Your menu doesn't do anything! Don't you need links to more pages?"*

With just HTML, we would. But that means repeating a lot of HTML and extra files.
So, our first step in automation should be [Chapter 4 - Javascript](chapter4.md)
# webdevops
[Intro](../README.md)

[Chapter 2 - CSS](chapter2.md) 
