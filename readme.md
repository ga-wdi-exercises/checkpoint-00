# Checkpoint 00

> **Fork and clone this repo and follow the directions below.**

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ). When you're done, submit this updated file as a pull request to this repo.

Please reference [this document](https://github.com/ga-dc/wdi16/blob/master/homework-policy.md#the-submission-process) for more information on how to submit this checkpoint.

## Javascript Variables and Data Structures

### Question 1

Create a variable and store the string "pizza" in it...

```js
var a = "pizza";
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
var names = ["Jonas", "Inigo Montoya", "Slim Shady", "Mr. Robot"];
for (var i = 0; i < arrayLength; i++);
var t = "Hello" + [i];
result t;
```

### Question 4

Access the value `"Alfred"` out of the `clown` object...

```js
clown.minions;
```

### Question 5

Set a new property on the object stored in the variable clown. Make it anything you want!

```js
clown.general= "assembly";
```

---

### Question 6
Write a function that takes an array as an argument and returns the array's first value...

```js
function array(ary, n) {
  var results = [];

}

```
---

## Git & GitHub

### Question 7

What is Git, what problem does it solve? What is the difference between Git and Github?

```
Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories. So they are not the same thing: Git the tool, GitHub the service for projects that use Git
```

---

### Question 8

What is the difference between a fork and a clone?

```
When you are Forking a repository you are creating a copy of repository under the GitHub Id. Any changes made to the original original repository will be reflected back to your forked repository. However, if you make any changes to your forked repository you will have to explicitly create a pull request to the original repository. When your pull request is approved by the administrator of the original repository, then your changes will be merged with the existing original code-base. Until then, your changes will be reflected only in the copy you forked. A Clone is where you have proper duplication, and separation between, two versions of a repository. When one repository is amended, the new content must be actively copied to the other repository using a push command. And changes in the other repository are fetched.


```

---

## HTML & CSS

### Question 9

How would you link a CSS file entitled `hardstyle.css` in an HTML file?

```html
<head>
<link rel="stylesheet" type="text/css" href="hardstyle.css">
</head>
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
#dog-resume { color: red }
```

### Question 11

Write a CSS selector-rule that will select and apply styling to every `<li>` inside of a `<ul>`:

```css
/* Answer goes here... */
```
