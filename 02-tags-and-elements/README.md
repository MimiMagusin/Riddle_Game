# Tags and elements

Now it is time to add our content! We not only should provide the browser
with the content itself, but also with its function. Is it a heading? A paragraph? An image?

🙋 *HTML (Hypertext Markup Language) is a markup language used to tell your browser how to **structure** your web page.*

For example, we could tell our browser that some content is a paragraph element by wrapping it in `<p> </p>` tags:

```HTML
<p>Answer all riddles correctly to find your way out...</p>
```

We have been talking about *tags* and *elements* for a while now, so let's have a look at what exactly we are talking about. [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started), a very helpful website made this overview:

![html element](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

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

>  🎓 **Add the content that you created in the last exercise to your page. Make sure everything is wrapped in an element with appropriate tags. My code looks something like this, now:**

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
