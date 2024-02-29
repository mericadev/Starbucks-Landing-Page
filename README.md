# Starbucks Landing Page 

This is a Starbucks recreation inspired by Pro Coder (https://youtu.be/MBUeNqQPsQE?si=YcwMzbUiZfPR4nKM). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Solution URL: ()

- Live Site URL: ()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
-  Vanilla JavaScript
- Flexbox
- Mobile-first workflow


### What I learned

Practiced how to create a sidebar for optimal user experience.


```css
.side-bar {
    display: none;
    flex-direction: column;
    position: fixed;
    top: 0;
    right: 0;
    height: 100vh;
    width: 400px;
    z-index: 999;
    background-color: hsla(0, 0%, 100%, 0);
    box-shadow: -10px 0 10px hsla(0, 0%, 0%, 0.2);
    backdrop-filter: blur(10px);
}
```

```html
<ul>
     <li class="location">
      <svg xmlns="http://www.w3.org/2000/svg" height="40" viewBox="0 -960 960 960" width="40"><path d="M480-480q33 0 56.5-23.5T560-560q0-33-23.5-56.5T480-640q-33 0-56.5 23.5T400-560q0 33 23.5 56.5T480-480Zm0 294q122-112 181-203.5T720-552q0-109-69.5-178.5T480-800q-101 0-170.5 69.5T240-552q0 71 59 162.5T480-186Zm0 106Q319-217 239.5-334.5T160-552q0-150 96.5-239T480-880q127 0 223.5 89T800-552q0 100-79.5 217.5T480-80Zm0-480Z"/></svg>
      <button>Find a store</button>


```

### Continued development

I aim to continue practicing my responsive design skills as well as use JavaScript for more interesting and responsive designs.



## Author

- Github - [@mericadev](https://github.com/mericadev)
- Twitter - [@merica_dev](https://www.twitter.com/merica_dev)


