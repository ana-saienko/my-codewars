# My Codewars Solutions

#### Convert boolean values to strings 'Yes' or 'No'. ####
**8 kyu**

```javascript
function boolToWord( bool ){
  if(bool === true){
    return "Yes"
  }else{
    return "No"
  }
}
```

#### Reversed Strings ####
**8 kyu**

```javascript
function solution(str){
  return str.split('').reverse().join('');
}
```

#### Grasshopper - Summation ####
**8 kyu**

```javascript
var summation = function (num) {
  let result = 0;
  for (let i = 0; i <= num; i++) {
    result += i;
  }
  return result;
}
```

#### Grasshopper - Summation ####
**8 kyu**

```javascript
var summation = function (num) {
  let result = 0;
  for (let i = 0; i <= num; i++) {
    result += i;
  }
  return result;
}
```

#### Square(n) Sum ####
**8 kyu**

```javascript
function squareSum(numbers){
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i] ** 2;
  }
  return sum;
}
```
