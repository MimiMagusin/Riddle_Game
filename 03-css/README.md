# CSS: Colors, Fonts and Backgrounds

Your index page looks something like this:

![Index Page](RG_index_unstyled.png)

A bit boring, still, right? Let's set some style! To do so, we'll need to write some CSS.

🙋 *CSS (Cascading Style Sheet) is used to style your web page.*

We need to tell our browser three things:

1) Which element(s) should be styled (**selector**)
2) What you want to change (**property**)
3) How it should be styled (**value**)

![selector, property, value](cssrule.png)

In this case, we want to style everything inside the body element, we want to change the color, and it should be gray.

🙋 *#333333 is a **hex color code**, representing the color grey. You can also mix your own color by using `rgb(r, g, b)` (see [this](https://htmlcolorcodes.com/) color picker to help you out) or by choosing one of the preset html colors (a list which can be found [here](https://htmlcolorcodes.com/color-names/)*

>  🎓 **Create a new file: `index.css`**

>  🎓 **Make sure your `index.html` knows about your new style sheet by adding the following code to your `<head> </head>` element:**

```HTML
<html>
  <head>
    <meta charset="utf-8">
    <title>Riddle game</title>
    <link rel="stylesheet" href="index.css">
  </head>
<!--leave the rest of the code as it is-->
```