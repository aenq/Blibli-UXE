# I. Written Test
<br>

## 1. What is a JavaScript Framework and explain about Vue.js as one of the JavaScript Framework!
Framework is a set of tool, approaches, or methodologies designed to help someone doing their job more easily, as in this context, JavaScript framework is a tool that help JavaScript Developer to simplify the process of building, developing, and standardizing software application. JavaScript has framework for both backend and frontend development, Vue.js is one of the popular JavaScript Framework specifically for frontend web development that offer simplicity and flexibility for building user interfaces. <br>

## 2. What is the use of ellipsis?
Ellipsis is used when the data is exceeds the available space in a design, we can truncate it to align with the design layout.
For example, Blibli has many products and there's maybe also many products name that longer than 20 characters. For the product card layout, let us say it's only display 20 characters, that means we have to truncate the name, that is when we can use Ellipsis. <br>


## 3. Explain animation properties below:
### a. @keyframes
`@keyframes` is a properties that we can use to make animation in CSS, we use @keyframes to define how our animation will move from start to finish, we can also use 0% that means the start of the animation to 100% which means the finish of animation.
This how `@keyframes` code look like:
```css
@keyframes AnimasiBergerak {
    0% {
        width: 180px
    }
    100% {
        width: 360px;
        height: 360px;
    }
}
```

### b. animation-name
`animation-name` is used to specify which `@keyframes` animation we want to use. 
Let's say we want to use AnimasiBergerak in element:
```html
<div class="box"></div>
```
We can specify the `@keyframes` AnimasiBergerak in css:
```css
.box {
    width: 180px;
    height: 180px;
    background-color: green;
    animation-name: AnimasiBergerak;
}
```

### c. animation-duration
We already know from the name that `animation-duration` is used to set the duration of the animation will move.
When we want the animation to move in 3 seconds, we write:
```css
.box {
    width: 180px;
    height: 180px;
    background-color: green;
    animation-name: AnimasiBergerak;
    animation-duration: 3s;
}
```


### d. animation-iteration-count
`animation-iteration-count` is used to set how many times an animation will looping or running. Let's say we want an animation to run 5 times looping before it stops, we can write:
```css
.box {
    width: 180px;
    height: 180px;
    background-color: green;
    animation-name: AnimasiBergerak;
    animation-duration: 3s;
    animation-iteration-count: 5;
}
```

### e. animation-direction
`animation-direction` used when we want to set how our animation will move, is it `normal` or `reverse`.
If we want it to be `reverse` then we can write:
```css
.box {
    width: 180px;
    height: 180px;
    background-color: green;
    animation-name: AnimasiBergerak;
    animation-duration: 3s;
    animation-iteration-count: 5;
    animation-direction: reverse;
}
```
<br>


## 4. Please explain how lazy load works in JavaScript!
Lazy load is an impactful technique for improving UX on a website, lazy load helps reduce the load time of a web page until the resources needed. <br>

## 5. Mention at least 5 git commands and describe each function of them!

### a. git add 
`git add` is used to add files or any changes that we want to add to our repo. To add all files in the directory to our repo is simply:
```git
git add .
```

### b. git commit 
`git commit` is used to put all the added files into a staging, we do this before actually push our code to the repo. We can use it by giving messages to the commit:
```git
git commit -m "UserActivityFeatures"
```
### c. git branch
`git branch` is to make a new branch. Let's say we are in development branch, and we want to make a new branch:
```git
git branch dev_another_branch
```

### d. git push
After we do add and commit command, we can `git push` our code straight to the github repo. We can use this command to push our code to master branch :
```git
git push origin master
```

### e. git checkout
When we work as a team, we can't work and push straight to the master branch, we have to work on our branch and pull request to the main branch when it all done. To move from master branch to our branch, simply use this command :
```git
git checkout [branch_name]
```

### f. git status
This command used for check if our code is had been added or not. Use it by running command:
```git
git status
```

### g. git clone
When you see a nice repo, and you want to learn from it locally in your device. Use this :
```git
git clone [url_repo]
```
