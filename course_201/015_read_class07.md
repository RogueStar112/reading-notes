[Back to Main Page](https://roguestar112.github.io/reading-notes/)

# Object-Oriented Programming, HTML Tables

## Domain Modeling

1. Explain why we need domain modeling.

Domain modelling is needed for Object Oriented Programming because
it allows you to create a representation of a solution to a problem.
For example, say if you wanted to make cars for a racing video game.

You would make a model around cars, with properties such as make,
model, and methods such as accelerate, brake, etc.

## HTML Table Basics

1. Why should tables not be used for page layouts?

- Accessibility limitations; Shifting through every table cell can be lengthy for screen readers.
- Tables can produce a lot of tags, each one for a row and individually for each cell. This can affect maintenance of the HTML.

2. List and describe 3 different semantic HTML elements used in an HTML `<table>`.

`<tr> - table row. This is the start of a new row in the table.`
`<th> - table heading. This is bolded, signifying it's a heading. This is typically used straight after a <thead> or the first <tr> element in a table.`
`<td> - table data. This is a generic table cell, in which 1 or more can exist inside of a <tr>.`

## Introducing Constructors;

1. What is a constructor and what are some advantages to using it?

Constructors allow you to dynamically create new objects, and update them as you code. In contrast to pure object literals, which don't have constructors, this is a game-changer.

2. How does the term `this` differ when used in an object literal versus when used in a constructor?

When using `this` in an object literal, you are referring to itself. When using a constructor, you are referring to the object created by that constructor.

<!-- When used in a constructor, you have to use `this` for every property you declare. For example, `this.carName = "Ford"`. This is different to object liter -->

## Object Prototypes Using A Constructor;

1. Explain prototypes and inheritance via an analogy from a previous work experience.

Imagine a car having its own prototype. That prototype is the foundation for future copies of the car. Inheritance means every copy of that car gets the same methods- Accelerate, Brake, etc.
