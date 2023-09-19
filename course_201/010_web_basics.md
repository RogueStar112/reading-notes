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
The abbr element allows you to expand on a term, so that it can be fully pronounced by a screen reader.

## Additional Sources used to answer questions:

1.

[About Screen Readers](https://blog.hubspot.com/website/screen-reader-accessibility);
