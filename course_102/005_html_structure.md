[Back to Main Page](https://roguestar112.github.io/reading-notes/)

## Quiz

1. *What is HTML and why do we use it?*

HTML stands for Hypertext Markup Language.
We use it to structure the layout of websites.

2. *What are the 3 main parts of an HTML element?*

    1. Opening tag
    
    2. Content

    3. Closing tag
       Note: Some elements don't have closing tags, such as img.

3. *What is it called when you give the element extra information?*

These are called attributes. Attributes can include classes, ids, etc.

4. *What is a semantic element?*

Semantic elements are both developer and machine readable by using full words.
For example, `<section>` and `<header>`
These can be understood more quickly than say, a `<div>` element, because
section and header don't require an attribute to explain its role.
div will require something like a class/id attribute to explain what it does.

## Extended Notes

<hr>

## Elaboration on Question 4

I will use pizza and salad as examples.

`<section>` and `<header>` do not necessarily need a class to describe what it does.

So something like `<section>pizza</section>` or `<section>salad</section>` is valid.

`<div class='pizza'>` or `<div class='salad'>` on the other hand, require the class/id attribute.



