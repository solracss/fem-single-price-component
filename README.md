# Frontend Mentor - [Single price grid component.](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Build out the project to the designs provided.
Your users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See a hover state on desktop for the Sign-Up call-to-action

### Screenshot

<details>

<summary>Click to open</summary>

![Desktop](https://i.imgur.com/j92eCSu.png)
![Mobile](https://i.imgur.com/n3K7s6x.png)

</details>

### Links

- Live Site URL: [Live](https://solracss.github.io/fem-single-price-component/)

## My process

### Built with

<div >
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML" title="HTML"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158956-48192682-23d5-4bfc-9dfb-6511ade346bc.png" alt="Sass" title="Sass"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" title="CSS"/>
</div>

### What I learned

1. Applying overlay background with pseudo.

```css
.why-us::before {
	content: "";
	position: absolute;
	top: 0;
	left: 0;
	height: 100%;
	width: 100%;
	background-color: #fff;
	opacity: 0.15;
}
```

2. Working with two column display using flexbox.
