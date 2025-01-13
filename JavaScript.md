# JavaScript Basic
**Ternary operator**  
It's a shortcut to if and else statements. The format is `condition ? codeIfTrue : codeIfFalse`    
**Arrays**
```javascript
let array = ["a","b","c"];
```
**Spread Operator**  
It's used for unpacking elements.
```javascript
let numbers = [1,2,3,4,5];
let maxmium = Math.max(...numbers);
```
**Rest Parameters**  
It's used for bundling seperate elements into an array, then pass it to the function.
```javascript
function sum(...numbers) {
    return numbers.reduce((total, num) => total + num, 0);
}
console.log(sum(1, 2, 3, 4)); // Output: 10
```
**Function**
```javascript
Function func(){

}
```
