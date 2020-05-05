## writeTextAnswer

```js
const user = {
  name: "Arya"
};
user.name = "Sansa";
console.log(user.name);
```

- Is the code above valid or invalid?
- Can we change the variable defined with const? Explain with reason.
- What will be the output and why?

## writeTextAnswer

1. What will be the value of a, b, x and y.

```js
let x = 10;
let y = "abc";
let a = x;
let b = y;
```

Answer:

---

2. What will be the value of a, b, x and y.

```js
var x = 10;
var y = "abc";
var a = x;
var b = y;
a = 5;
b = "def";
```

Answer:

---

3. What will be the value of `arr` and `arrCopy`.

```js
var arr = [1];
var arrCopy = arr;
arr.push(2);
```

Answer:

4. What will be the output and explain the reason.

```js
let obj = { name: "Arya" };
obj = { surname: "Stark" };
let newObj = { name: "Arya" };
let user = obj;
let arr = ["Hi"];
let arr2 = arr;
```

- `[10] === [10]`
- What is the value of obj? // answer
- `obj == newObj`
- `obj === newObj`
- `user === newObj`
- `user == newObj`
- `user == obj`
- `arr == arr1`
- `arr === arr1`

5. What's will be the value of `person1` and `person2` ? Explain with reason.

```js
function personDetails(person) {
  person.age = 25;
  person = { name: "John", age: 50 };
  return person;
}
var person1 = { name: "Alex", age: 30 };
var person2 = personDetails(person1);
console.log(person1);
console.log(person2);
```

```js
var brothers = ["Bran", "John"];
var user = {
  name: "Sansa"
};
user.brothers = brothers;
brothers.push("Robb");
console.log(user.brothers === brothers); //1. output
console.log(brothers.length === brothers.length); //2. output
```

## writeCode

What are the different ways of cloning an object? Clone below object.

```js
let charactor = {
  charactorName: "Sansa",
  sisters: 1,
  brothers: 4
};
```

## writeTextAnswer

```js
let brothers = ["John", "Bran", "Robb"];
let house = "Stark";
let user = {
  name: "Arya",
  house: house,
  brothers: brothers
};

let user2 = {
  name: "Arya",
  house: house,
  brothers: brothers
};

let user3 = {
  name: "Arya",
  house: "Stark",
  brothers: ["John", "Bran", "Robb"]
};
user.house === user2.house; // output:
user.house == user2.house; // output:
user.brothers === user2.brothers; // output:
user.brothers == user2.brothers; // output:
user.name == user2.name; // output:
user.name === user2.name; // output:
user.brothers == user3.brothers; // output:
user.brothers === user3.brothers; // output:
user.house === user2.house; // output
user.house === user3.house; // output
user.brothers[0] === user2.brothers[0]; // output
user.brothers[0] === user3.brothers[0]; // output
```
