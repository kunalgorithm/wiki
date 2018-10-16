
# TypeScript

Developers should be able to focus on creating amazing things. Code, at the end of the day, is just a tool to build amazing applications and experiences. However, developers often spend far more time understanding and maintaining code than writing new code.

With JavaScript, the larger a codebase gets, the harder it gets to maintain.

## Why not use TypeScript?
add a `// @ts-check` at the top of a Javascript file and get typechecking in it.

```typescript

// @ts-check
/**
* Format a price
* @param num {number} The price
* @param symbol {string} The currency symbol
*/
const formatPrice = (num, symbol = "$") => 
  `${symbol}${num.toFixed(2)}`;

formatPrice("1234");
```

## Resources

* [0-60 WITH TYPESCRIPT AND NODE JS](https://www.youtube.com/watch?v=vxvQPHFJDRo&t=1122s)
* [Why not use TypeScript?](https://medium.freecodecamp.org/why-would-you-not-use-typescript-67d0baa3eaca)
* [TypeScript - JavaScript with superpowers](https://medium.freecodecamp.org/typescript-javascript-with-super-powers-a333b0fcabc9)