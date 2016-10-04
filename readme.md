# Post Pre-Work Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```js
var food = pizza;
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

```
I understand the value jonas is inside an object and that to get a value out of an array I could use the .push method, but I wouldn't know how to answer this question correctly


```

---

### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (i=0; i<names.length ;i++){
  var name = [0]
  console.log("Hello", name);
}
```

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```js

```

---

## Git & GitHub

### Question 5

What is Git, what problem does it solve? What is the difference between `git` and github?

```
"Git is a version control software that lives within our local OS that we can use to keep track of a repository. It solves the problem of having an unclear or ineffective way of maintaining a version control. Also it always to go back in time and have access to files that we might have changed "
"Github is a remote version control system, while git is a local version control"

```

---

### Question 6

What is the difference between a fork and a clone?

```
when you fork a repository, you are cloning a copy of someone else's repository into your account. When you clone a repository you are copying a remote repository into your local repository.

```

---

## HTML & CSS

### Question 7

What does every HTML file need to be recognized as such? In other words, what do you need in each HTML file for it to be valid HTML?

```
a <!DOCTYPE html> to tell the browser what version of html is being used.
```

---

### Question 8

How would you link a css file entitled, `hardstyle.css` in an html file?

```
<link href="hardstyle.css" rel=stylesheet type="text/css">
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
 css-rule
}
```

---

### Question 10

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```
document.getElementByTag('li').className="dogSkill"

.dogSkill {
  css-rule
}
.. I forgot the selector to grab the child element for <ul>
```
