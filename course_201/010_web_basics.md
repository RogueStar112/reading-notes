[Back to Main Page](https://roguestar112.github.io/reading-notes/)

# 010 - Basics of HTML, CSS and JS

## Reading:

1. Why is it important to use semantic elements in our HTML?

According to MDN Web Docs, using semantic elements increases the
webpage's status ranking in search results.

Semantic elements allow for increased accessibility too. This makes it easier for screen readers to navigate through a webpage.

2. How many levels of headings are there in HTML?

There are 6 levels of headings, from biggest to smallest.

```html
<h1>
  <h2>
    <h3>
      <h4>
        <h5>
          <h6>
            <!-- <h7>, <h8>, onwards are not on the list. -->
          </h6>
        </h5>
      </h4>
    </h3>
  </h2>
</h1>
```

3. Some uses for sup and sub elements include:

- Dates.
  Example, `25<sup>th</sup>` March. This is displayed as 25<sup>th</sup>March.

- For mathematical numbers/equations, including powers.
  Example includes, `64<sup>2</sup>`. This is displayed as 64<sup>2</sup>.
- For scientific formulae, such as `H<sub>2</sub>O`. This is displayed as H<sub>2</sub>0.

4. When using the <abbr> element, what attribute must be added to provide the full expansion of the term?

You must add the 'title' attribute.
The abbr element allows you to expand on a term, so that it can be fully pronounced by a screen reader. For example, Serge. is expanded to Sergeant

## Learn CSS

1. We can apply CSS in 3 ways.

- Externally: by having a `<link rel="stylesheet" href="style.css"/>` element.
- Internal styling: by putting a `<style>` tag with CSS rules, or adding the `style` attribute
  to an element

2. We should avoid using inline styling because it mixes HTML with CSS in the attributes, making it harder to read and understand.

3. I'm going to break down this block of CSS code.

```css
h2 {
  color: black;
  padding: 5px;
}
```

The h2 represents the selector. `color: black;` and `padding: 5px;` are the declarations. and `color` and `padding` are the properties.

## Learn JS

1. Data types enclosed in single quotes/double quotes are strings. You may also use the backtick (`) key twice, to wrap a string literal.

2. Four types of Javascript operators.

- Mathematical operators, such as + (Add), \* (Multiply), - (Subtract), / (Divide)
- Assignment operator: =
- Comparison operator: == (equals), && (and).

3. A real world problem you can solve with a function for instance, is displaying food orders on the screen of a pizza delivery store. You'll have to display the customer's order, including pizza name, toppings, etc. This function will be called every time there is a customer order.

### Conditional statements

1. An if statement checks a boolean and if it evaluates to true, then the code block will execute.

2. Else if statements allow you to check for additional conditions in your code, that would otherwise be dismissed if you did not use it.

3. && (and), || (or), > (greater than).

4. The AND logical operator checks if two statements are true, whereas the OR checks if only one of them is true.

## Additional Sources used to answer questions:

1.

[About Screen Readers](https://blog.hubspot.com/website/screen-reader-accessibility);
