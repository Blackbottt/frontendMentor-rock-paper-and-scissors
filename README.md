# Frontend Mentor - Rock, Paper, Scissors solution

This is a solution to the [Rock, Paper, Scissors challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/rock-paper-scissors-game-pTgwgvgH). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the game depending on their device's screen size [ACHIEVED]
- Play Rock, Paper, Scissors against the computer [ACHIEVED]
- Maintain the state of the score after refreshing the browser _(optional)_
- **Bonus**: Play Rock, Paper, Scissors, Lizard, Spock against the computer _(optional)_

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Started project html and css to make background game outlook or html structure together with a rules button that is slightly hoverable and called it a day!
-

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Document Object Manipulation

### What I learned

-learnt how to use run and debug
-to console.log u go to the debug console
-if having problems configure microsoft edge launch.json file then launch edge then run and debugg
-also learnt that to change port of live server just visit live server extension settings then live server port .json file and change the port number
-to hide elements without them affecting the flow of elements on the page by not invisibly taking up space use display none then turn display on through javascript code down below
-the js func replay reload to page before user interaction
-to go a webpage back u can use window.location.back()

```js
const rulesDialogBoxOn = () => {
  return (rulesDialogBoxId.style.display = "flex");
};

const replay = () => {
  window.location.reload();
  return (scoreboard.textContent = score);
};
```

STEPS TO USING VS CODE DEV TOOLS:
-visit Microsoft edge tools
-launch project
-run n debug press play to launch edge as in launch project configuration with url pointing to live server url
-then on run and debug tools bar click open browser dev tools and mwala!!!!

proud of the following:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

<!-- If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more. -->

### Continued development

-currently struggling with how to end up using the jQuery library....
-how to console.log in this IDE
-struggled with clicking an option which causes an event with code that removes the element from the pages flow and replaces with another element had to rely on class actiong as on/off throught css visibility property
-learn more on state(refreshing and maintaining data)
-CSS responsive design

### Useful resources

- [resource 1](https://www.w3school.com) - This helped me as usual on randomizing computers choice

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
