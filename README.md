# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Captura de pantalla 2022-11-09 a las 11 05 08](https://user-images.githubusercontent.com/112894363/200894514-a5644c9d-0205-4479-bcad-993277b10e06.png)

![Captura de pantalla 2022-11-09 a las 11 04 52](https://user-images.githubusercontent.com/112894363/200894528-61b87f83-f6cf-4c06-bc51-9853fc698017.png)

### Links

- Solution URL: [https://github.com/bramizdev/profile-card-component-frontendmentor](https://github.com/bramizdev/profile-card-component-frontendmentor)
- Live Site URL: [https://bramizdev.github.io/profile-card-component-frontendmentor/](https://bramizdev.github.io/profile-card-component-frontendmentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I'm trying to improve the accessibility on my projects so I added some ```<span>``` elements with the class ```sr-only``` to describe further details of the user.

```HTML
    <h1 class="card-header">
      <span class="sr-only">User:</span> Victor Crest
      <span class="sr-only">Age:</span><span>26</span>
    </h1>
    <p class="card-country"><span class="sr-only">City:</span> London</p>
```

I used this code for CSS because I noticed that's the way Tailwind handles their ```.sr-only``` class.

```CSS
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border-width: 0;
}
```

### Useful resources

- [Tailwind Screen Readers](https://tailwindcss.com/docs/screen-readers) - This helped me to know what to include in the ```.sr-only``` class.

## Author

- Website - [Github @bramizdev](https://github.com/bramizdev)
- Frontend Mentor - [@bramizdev](https://www.frontendmentor.io/profile/bramizdev)

