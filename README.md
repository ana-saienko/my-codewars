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

#### Vowel Count ####
**7 kyu**

```javascript
function getCount(str) {
  var vowelsCount = 0;
  var vowels = ["a","e","i","o","u"];
  for(var i = 0;i < str.length;i++){
    for(var j=0;j<vowels.length;j++){
      if(str[i] === vowels[j]){
        vowelsCount++;
      }
    }
  }
  
  return vowelsCount;
}
```

#### Square Every Digit ####
**7 kyu**

```javascript
function squareDigits(num){
  let result = num
    .toString()                     // turn number to string
    .split("")                      // turn string into array
    .map( num => parseInt(num) )    // map each index and return a number, now you have a number array
    .map( num => num * num )        // map the number array and return the square of each number
    .join("")                       // turn the number array into a string
   
  return parseInt(result)           // turn the string into a number
}
```

#### Highest and Lowest ####
**7 kyu**

```javascript
function highAndLow(numbers){
  let array = numbers.split(" ");
  let big = Math.max.apply(null, array);
  let small = Math.min.apply(null, array);
  
  return `${big} ${small}`
}
```

#### Is n divisible by x and y? ####
**8 kyu**

```javascript
function isDivisible(n, x, y) {
  return n % x === 0 && n % y === 0
}
```

#### Basic Mathematical Operations ####
**8 kyu**

```javascript
function basicOp(operation, value1, value2) {
    switch (operation) {
        case '+':
            return value1 + value2;
        case '-':
            return value1 - value2;
        case '*':
            return value1 * value2;
        case '/':
            return value1 / value2;
        default:
            return 0;
    }
}
```
