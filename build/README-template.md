# Frontend Mentor - Notifications page solution

This is a solution to the [Notifications page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/notifications-page-DqK5QAmKbC). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Distinguish between "unread" and "read" notifications
- Select "Mark all as read" to toggle the visual state of the unread notifications and set the number of unread messages to zero
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Styled Components](https://styled-components.com/) - For styles


### What I learned
Empasis on conditioner rendering. and also how to selct one or group of nodes in html and do something to them


```html
        <nav>
            <div className="notification">
                <p>Notifications <span className="unread-num">{ unreadCount}</span></p>
            </div>
            <div className="mark-all">
                <button onClick={handleClickAll}> Mark all as read </button>
            </div>

        </nav>
```


### Continued development

conditioner rendering. and proper props drilling


### Useful resources
-- Chat-Gpt for breaking down problems and concept i struggle with
-- NetNinja react course on youtube did justice to the list problem i was having

## Author

- Website - [Adewale](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Alexhunts05](https://www.twitter.com/Alexhunts05)
