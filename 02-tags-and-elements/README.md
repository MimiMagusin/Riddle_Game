> ## Learning Goals
>🎯 By the end of this part, you will...
> 1. understand what is HTML is used for
> 2. know what an element is
> 3. know the basic structure of an html-page
> 4. know what tags are
> 5. be able to set display some basic content through html

# Tags and elements

Now it is time to add our content! We not only should provide the browser
with the content itself, but also with its function. Is it a heading? A paragraph? An image?

🙋 *HTML (Hypertext Markup Language) is a markup language used to tell your browser how to **structure** your web page.*

For example, we could tell our browser that some content is a paragraph element by wrapping it in `<p> </p>` tags:

```HTML
<p>Answer all riddles correctly to find your way out...</p>
```

We have been talking about *tags* and *elements* for a while now, so let's have a look at what exactly we are talking about. [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started), a very helpful website for developers, made this overview:

![html element](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

🙋 *If ever your page does not look like what you expected it to look like, check if all your elements have an opening and a closing tag! Indentation helps with this (you only have to scroll down to the next tag you come across), another of my favorite ways to check is by checking with `ctrl + F` or `cmd + F` and checking if there are an equal number of `<p>` and `</p>`, `<h1>` and `</h1>`, etc.*

Everything on your html page should be an element. Tags tell your browser what sort of element it is. Another example of a tag is the `<h1>` tag. You can use it for headings:

```HTML
<h1>Welcome Passenger</h1>
```

>  🎓 **Copy the code above inside the `<body></body>`. Your code should now look like this:**

```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Riddle game</title>
  </head>
  <body>
    <h1>Welcome Passenger!</h1>
  </body>
</html>
```

>  🎓 **Examples of other elements are: `<h2></h2>`, `<h6></h6>`, `<ul></ul>`, `<ol></ol>`, can you figure out what they do? Check out [this awesome MDN article](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) for help and some more useful elements. Make sure to try them on your page!**

>  🎓 **Add the content that you created in the first exercise to your page. Make sure everything is wrapped in an element with appropriate tags. My code looks something like this, now:**

```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Riddle game</title>
  </head>
  <body>
    <h1>Welcome Passenger</h1>
    <h2>You stepped into the labyrinth of life and death</h2>
    <h3>There is only one way out<h3>
    <h4>All other ways lead to eternity</h4>
    <h1>Muhahaha</h1>
    <h5>Answer all riddles correctly to find your way out...</h5>
  </body>
</html>
```
>  🎓 **Write a text that your players will see when they loose**

>  🎓 **In the same folder as you `index.html`, create a file `loose.html`**

>  🎓 **Add the basic html structure to that page. Make sure you have a DOCTYPE, an `<html> </html>` element, a `<head> </head>` element with a `<meta>` and `<title> </title>` element and a `<body> </body>` element**

>  🎓 **Add the text you wrote inside your `<body> </body>` element. Don't forget to wrap all your text in tags!**
