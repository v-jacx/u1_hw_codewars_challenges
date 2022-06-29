## Return Negative

```js
function makeNegative(num) {
  if(num > 0){
  num *= -1}
  
  return num;
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  
  arr.forEach((num)=>{
              if(num > 0){
                sum += num;
              }
              })
  return sum;
}
```

## Function 2

```js
const square =(num)=>{
  return Math.pow(num, 2);
}
```

## Sum Arrays

```js
function sum (numbers) {
    "use strict";
  let sum = 0;
    numbers.forEach((num)=>{
        sum += num;
    })
  return sum;
    
    
};
```

## Reversed Strings

```js
function solution(str){
  let reversed = '';
  
  for(let i=str.length; i>0; i--){
    reversed += str[i-1];
  }
  
  return reversed;
}
```
