# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot
Mobile <br>
![](/mobile%20Screenshot%202025-03-31%20at%2017-09-36%20Frontend%20Mentor%20Bento%20grid.png)

Desktop <br>
![](/desktop%20Screenshot%202025-03-31%20at%2017-10-09%20Frontend%20Mentor%20Bento%20grid.png)


### Links

- Solution URL: [here](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj)
- Live Site URL: [here](https://fem-bento-grid-raysh3n.netlify.app/)

## My process

### Built with


- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned



Possible to use nested CSS also
```css
	#grid-item-6 {
		grid-area: b6;


		h2 {
			font-size: 3.5rem;
			font-weight: var(--font-weight-400);
		}
	}
```



For the social media and calendar photos, learned that can use negative margin to hide some part of the pictures. 
```css
#grid-item-3 img {
	padding-top: 0.5rem;
	width: 12rem;
	margin-bottom: -2rem;
	text-align: left;
	margin-left: 0;
}

	#grid-item-3 {
		grid-area: b3;
		padding: 1rem;
		display: grid;

		img {
			margin-bottom: -6rem;
		}

	}
```


For the schedule social media image, used grid + max-width to achive the result for desktop version
```css
	#grid-item-2 {
		grid-area: b2;
		display: grid;
		overflow: hidden;

		img {
			max-width: 145%;
		}
	}
```






### Continued development
Write better CSS for this. 


### Useful resources
- [Kevin Powell bento Grid Challenge](https://www.youtube.com/watch?v=h4dHvo09cG4) - Learned about the image placement that requires the image to be cutoff. 

