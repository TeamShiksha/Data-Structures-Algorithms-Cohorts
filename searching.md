# Linear Search

In Linear Search we search through the array linearly . i.e one element after another

```javascript
let arr = [1, 2, 3, 4, 5, 6];
let numberToFind = 5;
function linerSearch(arr, numberToFind) {
  for (let number of arr) {
    if (number == numberToFind) {
      return true;
    }
  }
  return false;
}
console.log(linerSearch(arr, numberToFind));
```
Problem's to pratice : -
[Remove Dublicates from sorted array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
