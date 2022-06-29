## Return Negative

```js
function makeNegative(num) {
  return -Math.abs(num)
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  var negatives = []
  var sum = 0

  for (var i = 0; i < arr.length; i++) {
    if (arr[i] < 0) {
      negatives.push(arr[i])
    } else {
      sum += arr[i]
    }
  }

  console.log(negatives)

  return sum
}
```

## Function 2

```js
function square(num) {
  return num * num
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  var total = 0
  for (var i = 0; i < numbers.length; i++) {
    total += numbers[i]
  }
  return total
}
```

## Reversed Strings

```js
function solution(str) {
  return str.split('').reverse().join('')
}
```
