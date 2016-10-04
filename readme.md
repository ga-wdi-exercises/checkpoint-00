# Post Pre-Work Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```js
var x ='pizza';
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
names[0]
```

---

### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (i = 0; i < array.length; i++) {
  console.log(names[i]);
}
```

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1]
```

---

## Git & GitHub

### Question 5

What is Git, what problem does it solve? What is the difference between `git` and github?

```
Git is a program for your terminal that helps you organize, submit, and share your files remotely. It helps when your in a group with other people pushing changes to the files everyone is working on. Github is the actual place remote files are stored.

```

---

### Question 6

What is the difference between a fork and a clone?

```
You fork someone else's repository to your remote repository under your name. You clone a remote repository locally to make a new local repository.

```

---

## HTML & CSS

### Question 7

What does every HTML file need to be recognized as such? In other words, what do you need in each HTML file for it to be valid HTML?

```
<!DOCTYPE html>
```

---

### Question 8

How would you link a css file entitled, `hardstyle.css` in an html file?

```
<link rel="stylesheet" type="text/css" href="hardstyle.css">
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
#dog-resume {

}
```

---

### Question 10

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```
li {
  
}
```
