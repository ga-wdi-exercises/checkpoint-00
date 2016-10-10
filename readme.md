# Post Pre-Work/Week1 Quiz

#### ***Fork and clone this repo and follow the directions below.***

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it

```
var = "pizza"
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

```
var ['jonas']
```

---
### Question 3

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```
for(var i=0; 1 < names, i++){
  console.log('hello', names)
}
```

---


### Question 4

Access the value `"Alfred"` out of the `clown` object

```
var ('clown', 'enemy', 'minions'[Alfred])
```

---
### Question 5

Set a new property on the object stored in the variable clown. Make it anything you want!

```
clown = "heroes"
console.log(clown);
```

---
### Question 6
Write a function that takes an array as an argument and returns the array's first value

```
var minions=['robin', 'alfred']{
  console.log(minions);
  return(0);
}
```
--

## Git & GitHub

### Question 7

What is Git, what problem does it solve? What is the difference between `git` and github?

```
Git is a software we use locally to edit/save repositories and interact with Github. Github is an online source used to collaborate and share repos with others.

```

---

### Question 8

What is the difference between a fork and a clone?

```
A fork is how we get a copy of a repo on our github account. Cloning is how we access/save the repo locally so that we can make changes to it.

```

---

## HTML & CSS

---

### Question 9

How would you link a css file entitled, `hardstyle.css` in an html file?

```
No. You could, but I think you would have to manually change other things in order for it to actually work.

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
  text-align: right;
}

```

---

### Question 11

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```
ul li{
  font-weight: 200;
}
```
