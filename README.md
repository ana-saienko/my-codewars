# My Codewars Solutions

##### Convert boolean values to strings 'Yes' or 'No'. #####
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

##### Reversed Strings #####
**8 kyu**

```javascript
function solution(str){
  return str.split('').reverse().join('');
}
```

##### Grasshopper - Summation #####
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

##### Find the smallest integer in the array #####
**8 kyu**

```javascript
class SmallestIntegerFinder {
  findSmallestInt(args) {
     return Math.min(...args);
  }
}
```
