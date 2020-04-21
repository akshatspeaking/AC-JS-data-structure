# Data Structure (Array and Objects)

## Object-readText

- Objects are non-primitve data type.
- Use `{}` to define an object also known as Object Literal
- Objects are collection of `key` and `value` pairs seperated by comma.
- `key` and `value` is seperated by `:`
- `value` can be primitive or non-primitive data types.
- Objects are mutable (can be changed)
- Object does not retain the order you defined the keys.

Example:

```js
let user = {
  key: value
};
```

![Object](./assets/object.png)

There are operations like accessing, assigning, deleting or updating we can do on objects and their properties. To do this we can use two types of property accessors:

- Dot Notation (`.`)
- Bracket Notation (`[]`)

#### Dot Notation

```js
let username = {
  name: "Arya",
  house: "Stark",
  isAdult: true
};

// to access the value of key `name` using dot notation
console.log(username.name); // "Arya"
```

Using **DOT NOTATION** you can access the value of any key in object by specifying the name of the object (`username`) followed by `.` (dot notation), followed by the name of the key, like `username.name`.

While using `Dot Notation` you key value can only be **alphanumeric** (including `_` and `$`). Key name can't start with number.

**SUMMARY:**

- key can only be alphanumeric (including `_` and `$`)
- key cant start with number
- Can't access a key stored in variable

#### Bracket Notation

```js
let username = {
  name: "Arya",
  house: "Stark",
  isAdult: true
};
// to access the value of key `name` using bracket notation
console.log(username["name"]); // "Arya"
```

Using **BRACKET NOTATION** you can access the value of any key in object by specifying the name of the object (`username`) followed by key name (as string) in `[]` like `username["name"]`.

Bracket notation does two thing:

- Compute the value in `[]` (brackets)
- Access the value

What do I mean by above statements. Let's take an example

```js
var user = {
  arya: {
    age: 21
  },
  sansa: {
    age: 26
  }
};
let activeUser = "arya";

// to access the age of the "arya"
user[activeUser];
```

In above code `user[activeUser];` bracket notation does two thing

- Compute the value inside bracket notation. That means the value of activeUser is computed, that is "arya"
- Access the key (acces the arya key from object)

Another Example:

```js
let starks = {
  1: "Arya",
  2: "Sansa",
  3: "Rob"
};
// to access the key 1 from starks we can't use dot notation because dot notation doesn't support key starting with number or is a number. So we will use bracket notation
starks[1];
// Guess the value of code below
starks[6 - 5];

// output will be "Arya" because bracket notation does two thing. Compute the value inside bracket notation and access the value
```

**SUMMARY:**

- If accessing a key it should be in string
- You can use variable name, number etc.

//FEEDBACK: above two points are not clear.

#### Assigning, Re-assigning and deleting

```js
let username = {
  name: "Arya",
  house: "Stark",
  isAdult: true
};
```

To assign a new key value pair in object we can use either dot or bracket notation.

- to add/assign a new key-value pair in object we use assignment operator like `username.surname = "Stark";`.
- to re-assign a new value to key surname we can `username.surname = "Noone";`.
- `username.surname` will be `"Noone"`
- to delete a key we can use `delete` keyword like `delete username.surname`

## writeCode

Convert all of the above code to do the same using bracket notation.

```js
//1. add new key called surname and value "Stark"
//2. re-assign the value of surname key to "Noone"
//3. delete the key surname
```

## Array-readText

Array is a collection of only values, while keys are indexed (starts with 0 and keeps going up numerically).

- collection of values
- defined using `[]`
- keys are indexed (starts from 0 ...)
- Always use bracket notation to access it's values beacuse keys are number.
- Convention is to keep the values of array of same data types.

Example:

```js
// defining array
let starks = ["Arya", "Sansa", "Rob", "Bran"];

// accessing values
starks[0]; // "Arya"
starks[2]; // "Rob"
```

### Primitive vs Non-Primitive

**Primitive values are Immutable but Non-Primitive are mutable in nature.**

Example (Immutable): Applies to all primitive types

```js
let num = 21;
num = 30;
```

In above code you can see you are changing the value of `num` variable from 21 to 30. The whole value is changed.

```js
let user = {
  age: 21,
  name: "John"
};
user.age = 32;
```

In above code you can see you changed the value of `name` key of `user` object from 21 to 32. But the object assigned to `user` remained same. Means object can be mutated (changed).

## copy by value vs copy by reference-readText
