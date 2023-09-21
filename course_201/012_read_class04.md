[Back to Main Page](https://roguestar112.github.io/reading-notes/)

# 012 - HTML Links, JS Functions, and Intro to CSS Layout

## Questions

### Learn HTML

1. To create a basic link, we wrap text or other content inside what element?

We use the `<a>` tag, also known as the anchor tag.

2. The href attribute contains what information?

The `<a href=''>` attribute leads to the target address we're going to connect to.

3. What are some ways we can ensure links on our pages are accessible to all readers?

You can use the `title` attribute on `<a>`, which creates a description when hovering over it.

Screen readers read out loud the links, so the more concise your link description is, the better.
For instance, `Visit Google` is shorter and more concise than `Click here to go to Google`.

### Learn CSS Layout

1. What is meant by “normal flow”?

Normal flow is how content in a webpage flows without any CSS rules affecting it.

2. What are a few differences between block-level and inline elements?

- Content: `block-level` elements use up the remaining's parent's space, whereas inline elements simply display only within the content's boundaries.

```
Note: `<p>` elements automatically have a display of `block`.


```

-

3. \_\_\_ positioning is the default for every html element.

Every element has `static` positioning by default.

4. Name a few advantages to using absolute positioning on an element.

- Advantage: You can move an `absolute` positioned element within a relative parent element's boundaries, which can be very useful if you need to position an item in a very specific way.

- Advantage: Using the `z-index` attribute, you can overlap absolutely positioned elements.

- (bonus) Disadvantage: `absolute` positioned elements are **removed** from the original document flow, which is something to consider. Say if you wanted to wrap text around an image for instance. Absolute positioning will not achieve this.

- Conclusion: Using absolute positioning is best if you need to overlap content.

5. What is a key difference between fixed positioning and absolute positioning?

Fixed positioning is positioned based on the viewport's visible area, whereas absolute positioning changes position based on its nearest ascendant element (parent).

### Learn JS

1. A function declaration is when you define a function, whereas a function invocation is when you run the function by calling its name.

2. A parameter is the name of a variable stored inside of a function's parentheses (brackets).
   An argument on the other hand is the values put in the function's parentheses, in place of the parameters.

## Sources

- [MDN: Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

- [CSS-Tricks: Absolute Positioning](https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/)
