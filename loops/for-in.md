for-in loop is a type of loop used to iterate through a collection(an array)
thats basically where you will find yourself using it.

e.g 
```javascript
var fruits = ['orange','apple','grape'];
for(var fruitIndex in fruits){
    console.log(fruitIndex); // this will print out the index of all the array elements
    //output: 0 1 2

    console.log(fruits); // this will  print all the array elements

}
```