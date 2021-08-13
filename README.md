# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

### My approach
I used plain HTML and CSS Flexbox for this challenge.

### Difficulties faced
Adjusting the background image was tough. They tend to move with changing screen size. Other than that, everything went pretty smooth.

### Things I learned
For setting a background image on a blank section, we need to give it a fixed width and height (or min-height). Otherwise, it won't show since div is a block element and block elements have height according to their content. This div is blank and hence has a height of zero.
Another thing is that while trying to align different parts of any layout, it's always good to set a background or border on each of them to see what's happening as you change the stylesheet continuously.