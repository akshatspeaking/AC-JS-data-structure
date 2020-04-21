# Data Structure Assignments

## writeCode

Follow the instructions and write code just below the instruction.

- Create a variable named `character` using `let` and assign a value of blank object to it.

```js
// your code goes here
```

- Go to this [link](https://awoiaf.westeros.org/index.php/List_of_characters) and choose any charactor you like and click on the link. For example [Arya Stark](https://awoiaf.westeros.org/index.php/Arya_Stark)

```js
// your code goes here
```

- Re-assign the value of `character` variable to and object with the key `charaterName` and value of the first name of your character. example "Arya"

```js
// your code goes here
```

- A variable named `age` is predefined to 20. Add a new key named `character-age` with the value of age variable.

```js
let age = 20;
// your code goes here
```

- Add a new key named `surname` with the vlaue of the surname of the cahracter i.e "Stark"

```js
// your code goes here
```

- Add a new key named `title` with the value title of the character (you will find in the right side bar) i.e "Lady of Winterfell"

```js
// your code goes here
```

- Add another property named `greet` and value should be a function when called should alert `I am [NAME HERE] and my title is [TITLE HERE]`.

```js
// your code goes here
```

- Add a new property named `isFemale` and value will be either `true` or `false` according to the character.

```js
// your code goes here
```

- Change the method `greet` to now alert `He is [NAME HERE] and his title is [TITLE HERE]` if the character is male or else `She is [NAME HERE] and her title is [TITLE HERE]`. You should use `if/else`.

```js
// your code goes here
```

- Add a new method (function inside objects are called methods) named change gender. When called should be able to flip the value of `isFemale`.

```js
// your code goes here
```

- Check by calling `greet` and see if the message is changed or not.

```js
// your code goes here
```

- `let keyName = "playedBy";`- Add a new key with the value stored in `keyName` variable the value of the played by in right side bar. (use the variable name to do this)

//FEEDBACK: Above line is not clear, especially second part of the sentence.

```js
// your code goes here
```

- `alert` the value of key stored in `keyName` variable.

```js
// your code goes here
```

- Write a `for..in` loop to `console.log()` all the keys of the object character.

```js
// your code goes here
```

- Write a `for..in` loop to log the all the key value pair seperated by `-` like `characterName - Arya`.

```js
// your code goes here
```

- Using the function `console.log` to log the value of the key `42`.

```js
// your code goes here
```

- Add a key in your object with the value of the variable `city`. The value of the key should be `true`.

```js
// your code goes here
```

```js
var city = prompt("Enter the city name you visited las time.");

// your code goes here
```

- Uisng console.log log the value of the key defined above.

```js
// your code goes here
```

-. Can you define a key of `let or var` in any object? Reason.

```js
// your code goes here
```

## writeTextAnswer

```js
let keyValue = "username";
let character = {
  username: "arya"
};
// 1.
console.log(character["keyValue"]);
// 2.
console.log(character[keyValue]);
```

- What will be the output of 1 and 2.
- Why are they different.
- Can I use `.` dot notation to access the value (using variable name). Write reason.
- What is the difference between `.` dot notation and `[]` bracket notation. Example
- What are situation where we use dot notation and bracket notation.

## writeQuiz

Whic statement is true?

- [ ] You can replace all dot notation with bracket notation.
- [ ] You can replace all bracket notation with dot notaiton.

## Array-writeCode

- Create an array named colors that contains five different names of colors as strings.

```js
// your code goes here
```

- Access the first color in the array and print it to the console using `console.log()`

```js
// your code goes here
```

- Now do the same with the third color in the list.

```js
// your code goes here
```

- Re-assign the value of the last color in array to "ultraviolet".

```js
// your code goes here
```

- Re-assign the value of the last color in array to "ultraviolet". This time use `arr.length` property to know the length of the array.

```js
// your code goes here
```

- Create a new variable called fourthColor and set it equal to the fourth color in the list.

```js
// your code goes here
```

- Add another color to the end of the list. (use array method called push)

```js
// your code goes here
```

- Add another color to the beginning of the list. (use unshift)

```js
// your code goes here
```

- Print the length of the array to the console with `console.log()`

```js
// your code goes here
```

- Remove the last color from the end of list, and then print the length of the array to the console one more time.

```js
// your code goes here
```

- Write a for loop to iterate through every color in the array and print each color's value to the console.(use for loop)

```js
// your code goes here
```

- Write a for loop to iterate through every color in the array and print each color's value to the console.(use for..in)

```js
// your code goes here
```

- Write another loop to display the value and key of array in this format. `The value for index 0 is Red` for each value.

```js
// your code goes here
```

- Create a variable named `lastColor` that will always point to the last element of the colors array, no matter how many colors are in the list.

```js
// your code goes here
```

- Add a new color `tomato` to the index 45. And check the length of the array. Use `console.log` to print.

```js
// your code goes here
```

## writeTextAnswer

What will be the output if you access index greater than the length of the array. Like array length is 10 and `arr[11]`. Same with object if you access the key that doesnot exist.
