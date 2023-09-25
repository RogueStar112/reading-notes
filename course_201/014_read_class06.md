[Back to Main Page](https://roguestar112.github.io/reading-notes/)

1. How would you describe an object to a non-technical friend you grew up with?

Imagine taking apart any object, like a car for instance. The parts may be: the car frame, wheels, steering wheel, engine, etc. If one of these parts were absent, the car wouldn't function.

2. What are some advantages to creating object literals?

You can send multiple values in a single object literal, in contrast to sending each value individually.

For instance:

```js

let object = {
  name: 'Demie'
  age: 24
  isGamer: true
}

// vs.

let name = 'Demie'
let age = 24
let isGamer = true;

```

The top object defines a person's characteristics in one variable, whereas the bottom one required three!
Not only do objects make storing values more compact, it also makes it easier to access such values, such as with a loop.


3. How do objects differ from arrays?

Arrays store multiple kinds of data, each with their own numeric index. While arrays also store multiple kinds of data, Objects' indexes are given names through **keys**.

Array elements can be accessed through [ ] notation, whereas objects also use this, but they can also be accessed through dot notation.

So with the code example above, object.name, or object['name'] gives out 'Demie'.


4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
