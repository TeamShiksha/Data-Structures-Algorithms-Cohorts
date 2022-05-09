# Linear Search

In Linear Search we search through the array linearly . i.e one element after another
 we start from one end and check every element of the list until the desired element is found.
```javascript
let arr = [1, 2, 3, 4, 5, 6];
let numberToFind = 5;
function linearSearch(arr, numberToFind) {
  for (let number of arr) {
    if (number == numberToFind) {
      return true;
    }
  }
  return false;
}
console.log(linearSearch(arr, numberToFind));
```

Problem's to pratice : -

[Remove Dublicates from sorted array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
