## Return Negative

```js
function makeNegative(num) {
  // Code?
  if (num > 0) {
    return num * -1;
  } else return num;
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  for (i = 0; i < arr.length; i++) {
    if (arr[i] >= 0) {
      sum += arr[i];
    }
  }
  return sum;
}
```

## Function 2

```js
function square(num) {
  num = Math.pow(num, 2);
  return num;
}//Math.pow found here: https://www.w3schools.com/js/js_math.asp
```

## Sum Arrays

```js
function sum(numbers) {
  "use strict";
  let total = 0;
  for (let i = 0; i < numbers.length; i++) {
    total += numbers[i];
  }
  return total;
}
// for some reason, it didn't like my for loop unless I declared the i iterator with "let", which I've never had to do before - I'm guessing this is part of "use strict"?
```

## Reversed Strings

```js
function solution(str){
  stringArray = str.split(""); // .split - JavaScript method that converts a string to an array
  backwardsString = stringArray.reverse(""); // .reverse - JavaScript method that reverses the order of an array
  finalString = backwardsString.join(""); // .join - JavaScript method that joins array elements into a string
  return finalString;
} 
```
