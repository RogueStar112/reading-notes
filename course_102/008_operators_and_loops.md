[Back to Main Page](https://roguestar112.github.io/reading-notes/)

# 008 - Operators and Loops

## Answers to Reading Questions

1. What is an expression in JavaScript?

An expression is any set of values that evaluates to return a result. It can be any data type, from integer to string.

Examples include

```js

1; // 1
5 + 5; // 10 
let name = 'Demie';


```


2. Why would we use a loop in our code?

If you need a way to repeat your code without doing it manually by hand every time, loops are required.

3. When does a for loop stop executing?

It stops executing when its given condition returns `false`. For example

```js

// prints 10 times. When i is no longer less than 10, the loop stops.
for(let i=0; i<10; i++) {

    console.log(i);

}

```

4. How many times will a while loop execute?

A while loop will keep executing its code until its given condition is `false`.

```js

// This means...
while(true) {
    // Runs infinitely! This is because the true condition is set in stone until you close the code.
}

// 



```

