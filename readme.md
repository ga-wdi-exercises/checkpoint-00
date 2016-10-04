# Post Pre-Work Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

var = "pizza"

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

names[0]

---

### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

var names = ["Jonas", "Inigo Montoya", "Slim Shady", "Mr. Robot"];
var sayHello = function() {
  for(var i=0; i<=names.length; i++) {
    sayHello();
  }
}
console.log('hello');

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

clown['Alfred']

---

## Git & GitHub

### Question 5

What is Git, what problem does it solve? What is the difference between `git` and github?

Git is a form of version control. It solves the problem of having to create multiple versions of a file to track changes and makes these  changes easier to identify.

Git is the tool used to create and edit files, Github is a remote domain that hosts repositories of files.

---

### Question 6

What is the difference between a fork and a clone?

Forking means to create a copy of the files in a repository, to your github account's repository so that you can edit your version of the code . Cloning means to transfer the repository's files from the remote location to the local server, thus making a local copy.

---

## HTML & CSS

### Question 7

What does every HTML file need to be recognized as such? In other words, what do you need in each HTML file for it to be valid HTML?

in every html file we need to do write the following to make it a valid html

<html>
<!DOCTYPE html>
</html>

we do this as format so that the browser recognizes that we are running the html file, it it just standard formality
---

### Question 8

How would you link a css file entitled, `hardstyle.css` in an html file?

it goes the head of the document before before the body
<html>
<!DOCTYPE html>
<header></header>
<link href='hardstyle.css' rel='stylesheet'>
<body></body>
</html>

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


div {
  padding: 0 auto;
}


---

### Question 10

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

li {
  display: inline;
}
