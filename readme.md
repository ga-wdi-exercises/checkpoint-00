# Checkpoint 00

> **Fork and clone this repo and follow the directions below.**

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ). When you're done, submit this updated file as a pull request to this repo.

Please reference [this document](https://github.com/ga-dc/wdi16/blob/master/homework-policy.md#the-submission-process) for more information on how to submit this checkpoint.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it...

```js
var "pizza";
```

---

>  **For questions 2-5, use the code below to answer questions 2 through 4.**

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

### Question 2

Access the value `"Jonas"` out of the `names` array...

```js
names[0];
```

### Question 3

Write a for loop that prints `hello NAME` to the console. `NAME` should be replaced with a name that appears in the `names` array. Each iteration of the loop should print a different name.

```js
for (i = 0; i < names.length; i++) {
  console.log("hello " + "names[i]");
};
```

### Question 4

Access the value `"Alfred"` out of the `clown` object...

```js
clown.minions[1];
```

### Question 5

Set a new property on the object stored in the variable clown. Make it anything you want!

```js
clown.minions[1] = "Fitssum";
```

---

### Question 6
Write a function that takes an array as an argument and returns the array's first value...

```js
var sum = function (x, y) {
  return x + y;
};

var name = function ("Jonas", "Slim Shady"){

  return "Jonas " + "is " + "the " + "brother " + "of " + "Slim Shady."
}
```
---

## Git & GitHub

### Question 7

What is Git, what problem does it solve? What is the difference between Git and Github?

```
# Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories.
```

---

### Question 8

What is the difference between a fork and a clone?

```
# Fork allows to copy a version of a repo to my own own GitHub account. Clone makes local copy of the fork.

```

---

## HTML & CSS

### Question 9

How would you link a CSS file entitled `hardstyle.css` in an HTML file?

```html
<!-- Answer goes here... -->
<link rel="stylesheet" href="styles.css">

```

---

> **For Questions 10 & 11 use the code example below...**

```html
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
```

### Question 10

Write a CSS selector that will apply styling to an element with an id of `dog-resume`...


```css
#dog-resume {
  Align text: right;
 }
```

### Question 11

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```css
.skillz li {
  font-family: Times New Roman;
}

```
