[Back to Main Page](https://roguestar112.github.io/reading-notes/)


1. What is the purpose of CSS?

CSS allows you to make your webpages have visuals
that would otherwise not be possible without it. Adding text/background colors, margin/padding,
and font styles are examples of what CSS can do.

2. What are the three ways to insert CSS into your project?

    1. You can insert the CSS as an external file in your HTML file.
       using `<link rel="stylesheet" href="style.css">`

    2. You can add CSS internally in your HTML file using the `<style>` tag.
    e.g. `<style>p { color: blue; }<style>`. 

    3. You can also add the style attribute to HTML tags. e.g. `<p style="color: blue" >I'm blue</p>`
    
    Both methods 2 and 3 aren't ideal, as it breaks the
    separation of concerns rule. (Separating HTML, CSS and JS independently.)

3. Write an example of a CSS rule that would give all `<p>` elements red text.

```
p {
    color: red;
}
```
