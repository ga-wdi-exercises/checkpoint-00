# Post Pre-Work Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```js
var food = "pizza";
```

---

>  ***For questions 2-4, use the code below to answer questions 2 through 4.***

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
names[0];
```

---

### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (var i = 0; i < names.length; i++) {
  console.log(`hello, ${names[i]}`);
}
```

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```

---

## Git & GitHub

### Question 5

What is Git, what problem does it solve? What is the difference between `git` and github?

```
Git offers a way to track different versions of files in a single repository, allowing us a systematic way
to manage development and collaborate.

git is the actual version control system and github is git made into SaaS.
```

---

### Question 6

What is the difference between a fork and a clone?

```
A fork is a remote copy of a repository and a clone is a local copy.
```

---

## HTML & CSS

### Question 7

What does every HTML file need to be recognized as such? In other words, what do you need in each HTML file for it to be valid HTML?

```
doctype defining html
opening and closing html, head, body tags. meta tags are also a good practice to have

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

---

### Question 8

How would you link a css file entitled, `hardstyle.css` in an html file?

```
<link rel="stylesheet" href="hardstyle.css">
```

---

> ##### For Questions 9 & 10 use the code example below:

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

### Question 9

Write a CSS selector-rule that will select and apply styling to an element with an id of `dog-resume`:


```
div#dog-resume
```

---

### Question 10

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```
ul>li
```
