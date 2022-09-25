# Frontend Mentor - Notifications page solution

This is a solution to the
[Notifications page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/notifications-page-DqK5QAmKbC).

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   Distinguish between "unread" and "read" notifications
-   Select "Mark all as read" to toggle the visual state of the unread
    notifications and set the number of unread messages to zero
-   View the optimal layout for the interface depending on their device's screen
    size
-   See hover and focus states for all interactive elements on the page

### Links

-   Solution URL:
    [samantha-lind/notifications-page](samantha-lind/notifications-page)
-   Live Site URL:
    [https://singular-monstera-1a3652.netlify.app/](https://singular-monstera-1a3652.netlify.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Vanilla JS

### What I learned

The simplest way to limit a function to one use is to remove the Event Listener
as part of the function.

If flex isn't aligning your content vertically, make sure the body is set to at
least 100vh.

A margin set to auto will try to become as big as it can in the direction it has
been set in:

-   In the case of using margins to center a block, we set the left and right
    both to auto; they each try and take up as much space as possible and so
    push our block into the center.
-   To align an item to the right, give it a margin-left of auto. This then
    means that the margin tries to get as much space as possible to the left of
    the item, which means the item gets pushed all the way over to the right.

Adding a border on hover may make an image shift by a few pixels. Avoid this by
adding a transparent border to the original.

### Useful resources

-   [Flex alignment](https://www.smashingmagazine.com/2018/08/flexbox-alignment/) -
    This helped me when I couldn't align the picture comment to the far right of
    the div.

## Author

-   Website - [Samantha Lind](https://www.samanthalind.net)
-   Frontend Mentor -
    [@ysamantha-lind](https://www.frontendmentor.io/profile/samantha-lind)
-   GitHub - [@samantha-lind](https://www.github.com/samantha-lind)
