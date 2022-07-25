# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [GitHub Repository](https://github.com/joanFaseDev/preview-card)
- Live Site URL: [Project hosted throught Vercel](https://preview-card-phi.vercel.app/)

## My process

### Analysis

- Two different designs, a mobile and a desktop one, so the page would be responsive.
- Card can be divided in three main parts: photo, text (title &sol; paragraph) &sol; metrics
- Can use CSS Grid here:
  - One column and three rows for the mobile design
  - Two columns and three rows for the desktop design
- At one point, use _media queries_ to change column numbers and switch from mobile design to desktop one.
- Will start by mobile design because it's easier to add complexity to a design than to remove it (mobile design have less space to cover and less elements to display so it's ofter better to start mobile first). Plus nowadays, most people use the web through mobile devices to it makes senses to focus the experience on the many instead of the few.
- Title seems to be bigger in desktop design but the other entries don't seem to change size.
- There's two images, one for the mobile design and the other for the desktop design. Will use the _picture_ and _source_ elements to make the switch.
- Both images are black &sol; white so we'll use _linear-gradient()_ to add the purplish color on top of it.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [MDN article on the _picture_ HTML element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This helped me make the switch between the image from the mobile design and the one from the desktop design.

- [MDN article on the CSS _filter_ property](https://developer.mozilla.org/en-US/docs/Web/CSS/filter) - This helped me partially reproduce the purplish filter on the card's photo.

- [CSS Image Overlay](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) - An article by Ellen Macpherson on how to easily apply a color overlay on an image HTML element (or not).

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
