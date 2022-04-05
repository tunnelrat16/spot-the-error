# Spot The Error

There are at least 5 errors in this code:

```js
// This function is supposed to accept a count, and for the numbers 1 up to and including that count:
// * Print "fizz" if the number is divisible by 3
// * Print "buzz" if the number is divisible by 5
// * Print "fizzbuzz" if the number is divisible by 3 and 5
// * Otherwise print the number

function printFizzBuzzNumbers(count){
  const fizzBuzzNumbers = []

  for (let i = 0; i < count; i++) {
      const isDivisibleBy3 = i % 3 === 0;
      const isDivisibleBy5 = i % 5 === 0;

      if (isDivisibleBy3) {
        fizzBuzzNumbers.push(i)
      }
      if (isDivisibleBy5) {
        fizzBuzzNumbers.push(i)
      }
      if (isDivisibleBy3 && isDivisibleBy5) {
        fizzBuzzNumbers.push(i)
      }
      fizzBuzzNumbers.push(i)
  }
}
```

Use reflection techniques and sample data to discover them. **Don't try to run the code**. Edit the function above as minimally as possible to correct the errors you find.
