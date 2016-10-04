# Post Pre-Work Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```js
answer goes here
```
var food = "pizza"

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
answer goes here
```
names[0]

---

### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
answer goes here
```
var names = ["Jonas", "Indigo Montoya", "Slim Shady", "Mr. Robot"]
for (i = 0; i < names.length; i++) {
  console.log(names[i])
}

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```js
answer goes here
```
clown.enemy.minions[1]


---

## Git & GitHub

### Question 5

What is Git, what problem does it solve? What is the difference between `git` and github?

```
answer goes here

```Git is a software that open source projects. Github is a company that hosts Git repository.

---

### Question 6

What is the difference between a fork and a clone?

```Fork is used to create a copy of a project hosted on a GitHub users account. Clones use git software on your computer to download the source code and its entire version.
answer goes here

```

---

## HTML & CSS

### Question 7

What does every HTML file need to be recognized as such? In other words, what do you need in each HTML file for it to be valid HTML?

```
answer goes here     <!DOCTYPE html>, which tells the text editor the document is HTML5
```

---

### Question 8

How would you link a css file entitled, `hardstyle.css` in an html file?

```In my html file, I'd use the code "<link rel="stylesheet" type="text/css" href="mystyle.css">" between my <head></head> tags.

<link rel="stylesheet" type="text/css" href="hardstyle.css">

answer goes here
```

---

> ##### For Questions 9 & 10 use the code example below:

```HTML
<!-- ...html stuff above -->
<body>
  <div id="dog-resume">
    <ul class="skillz">
      <li class="skillz"> - Bone Location</li>
      <li class="skillz"> - Remote Sniffing</li>
      <li class="skillz"> - Delineating Territory</li>
      <li class="skillz"> - Shoe Deconstruction </li>
      <li class="skillz"> - Carpet Stain Placement </li>
    </ul>
  </div>
</body>
<!-- html stuff below... -->
```

### Question 9

Write a CSS selector-rule that will select and apply styling to an element with an id of `dog-resume`:


```
answer goes here #dog-resume {
  .....
}
```

---

### Question 10

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

``` ul li {
  
}

answer goes here
```
