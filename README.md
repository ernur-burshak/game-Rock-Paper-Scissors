# SuperSimpleDev - game Rock Paper Scissors

This is a mini-project from the [JavaScript Tutorial Full Course - Beginner to Pro (2024)](https://www.youtube.com/watch?v=EerdGm-ehJQ&t=29617s). The course helped improve my coding skills by creating realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/ernur-burshak/game-Rock-Paper-Scissors)
- Live Site URL: [Add live site URL here](https://ernur-burshak.github.io/game-Rock-Paper-Scissors/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JS event, button and key interactions
- JS advanced functions

### What I learned

```js
document.querySelector(".js-auto-play-button").addEventListener("click", () => {
  autoPlay();
});
```

```js
setInterval(() => {
  const playerMove = pickComputerMove();
  playGame(playerMove);
}, 1000);
```

```js
document.body.addEventListener("keydown", (event) => {
  if (event.key === "r") {
    playGame("Rock");
  } else if (event.key === "p") {
    playGame("Paper");
  } else if (event.key === "s") {
    playGame("Scissors");
  } else if (event.key === "a") {
    autoPlay();
  } else if (event.key === "Backspace") {
    showResetConfirmation();
  }
});
```

### Continued development

In the future, I want to work on a big project.

### Useful resources

- [the JS course](https://www.youtube.com/watch?v=EerdGm-ehJQ&t=29617s) - The course helped improve my coding skills by creating realistic projects.
- [auxiliary for studying](https://github.com/SuperSimpleDev/javascript-course/tree/main/1-exercise-solutions) - There are solutions for the entire course task.

## Author

- Website - [Ernur](https://ernur-burshak.github.io/game-Rock-Paper-Scissors/)

## Acknowledgments

In this project, I am very grateful to the author of the SuperSimpleDev course, he explains it very clearly, he taught me the basics of JS. I am glad that I met such a teacher, thank you!
