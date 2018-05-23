# Making our browser understand

## But first.... content

We'll start our game with introducing our story line. Let's start with the content. In our case, that will be:

*Welcome Passenger*

*You stepped into the labyrinth of life and death*

*There is only one way out*

*All other ways lead to eternity*

*Muhahaha*

*Answer all riddles correctly to find your way out...*

>  🎓 **Write a short intro to your game on a piece of paper or in your favorite text editor (word, notepad, atom or visual studio code).**

## Making your browser understand

Now you wrote your content, we have to make sure your browser understands it as well.

🙋 *Some examples of browsers are: Chrome, Firefox, Microsoft Edge, Safari*

We can do this by creating an html file in a text editor such as Atom or Visual Studio Code.

> 🎓 **Create a new folder on your desktop. Call it `riddle-game`. Make sure you don't use any spaces in the name!**

> 🎓 **In atom, choose `File > Add Project Folder` and select your new directory `riddle-game`**

> 🎓 **Create a new file called `index.html` This is where you will write your code!**

HTML will translate and structure our content in such a way that your browser will understand what to do with it.   

🙋 *An **HTML file** is a webpage coded in HTML that can be **displayed in a web browser**. It is used to **format** text, tables, images, and other content that is displayed on a webpage.*

The first clue to browser that we will feed it some information that it will understand is the name of the file we just created, using the `.html`*-extension*. However, browsers like to be super sure about of the type of page they are opening. That is why we will have to wrap our content in the following code:

```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Riddle game</title>
  </head>
  <body>
    <!-- This is where you will write your
    content that will display on the page! -->
  </body>
</html>
```
🙋 *Did you notice that some lines start further to the right than others? This is called **indentation**. It is a nice way to quickly see which elements are inside other elements. For example, the `<meta>` and the `<title> </title>` elements are inside the `<head> </head>` element (but not in the `<body> </body>` element) and the `<head> </head>` and the `<body> </body>` elements are in the `<html> </html>` element.*

We are giving our browser several strong clues that the next things we will write will be HTML:

* First we announce that the file below will be an html file by declaring  `<!DOCTYPE html>` (I always like to think we need capitals because browsers are a little deaf)
* Next we tell our browser exactly where are html starts and ends: it starts after the first `<html>` tag and ends with the `</html>` tag.

Next up, we divide our html file up in a `<head></head>` and a `<body></body>` section. In our `<head></head>` section, we give the browser some information about our page, such as which characters it can use on your web page (`<meta charset="utf-8">`) and what title it should display in the tab/window of your browser (`<title>Riddle game</title>`)

> 🎓 **Copy  the code above in your `index.html` and open the file in your browser (File > Open). It will open an empty page, but do you see how the title in your tab changed to *'Riddle Game'*?**
