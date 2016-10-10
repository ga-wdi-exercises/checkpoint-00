# Post Pre-Work/Week1 Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```js

var x = "pizza";

```

---

>  ***For questions 2-5, use the code below to answer questions 2 through 4.***

```js
var names = ["Jonas", "Inigo Montoya", "Slim Shady", "Mr. Robot"];
var clown = {
  name: "Joker",
  evil: true,
  minions: ["Bozo", "Harley Quinn", "Grumpy", "Chuckles"],
  enemy: {
    name: "Batman",
    evil: false,
    minions: ["Robin", "Alfred"]  
  }
};
```

---

### Question 2

Access the value `"Jonas"` out of the `names` array:

```js

console.log(names[0]);

```

---
### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
var names =["a","b","c"]
for(i=0; i<names.length;i++);
console.log("hello " + names[i]);

```

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```js

clown.enemy.minons[1];

```

---
### Question 5

Set a new property on the object stored in the variable clown. Make it anything you want!

```js

var x = ["good"];

var clown = {
  x: false,
};

```

---
### Question 6
Write a function that takes an array as an argument and returns the array's first value

```js
var names =["a","b","c"]
function names() {
  console.log(names[0]);
}

```
---

## Git & GitHub

### Question 7

What is Git, what problem does it solve? What is the difference between `git` and github?

```
Git is a version control software program that allows you to track and save different versions of your work. It solves the problem of seeing the changes you've made on your code and the problem of efficiently and effectively working collaboratively with others. Github is an online server where you store files to share and also where you download files.

```

---

### Question 8

What is the difference between a fork and a clone?

```
Fork is when you copy from another repository online on github.
A clone is when you copy from your repository onto your local drive.

```

---

## HTML & CSS

---

### Question 9

How would you link a css file entitled, `hardstyle.css` in an html file?

```
<link ref="hardstyle.css"></link>
```

---

> ##### For Questions 10 & 11 use the code example below:

```HTML
<!-- ...html stuff above -->
<body>
  <div id="dog-resume">
    <ul class="skillz">
      <li> - Bone Location</li>
      <li> - Remote Sniffing</li>
      <li> - Delineating Territory</li>
      <li> - Shoe Deconstruction </li>
      <li> - Carpet Stain Placement </li>
    </ul>
  </div>
</body>
<!-- html stuff below... -->
```

### Question 10

Write a CSS selector-rule that will select and apply styling to an element with an id of `dog-resume`:


```
#dog-resume{

}
```

---

### Question 11

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```
ul > li{

}
```
