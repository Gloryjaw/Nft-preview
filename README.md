# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learned about behaviour of image as flex items.
Flex direction :row

 --> If the flex direction is row then the flex items are streched to the height of Flex container. If flex container does not have height then the height of flex items will be streched to the height of that flex itmes which have more height than other. 
 --> Images as flex items are not by default responsive. And streching the height of image will also change it width to maintain aspect ratio(if the width of image is not set). If there is only one flex item which is image then image will take its default size.
 --> Flex container does its best to shrink the flex itmes so that they remain inside flex container. It will also try to shrink image if the width of image is too much(bigger than the flex container)

 Flex direction: column

 --> By default images are responsive because images are strech their width to the width of flex container. Since width is by defualt responsive, images will decrease and increase its own width to maintain its streching and with its width, its height will also increase and decrease according to aspect ratio. Hence, it gives images responsive nature as flex itmes if flex direction is column.

 Learned how to affect other elements when one element is hovered
 --> Here is the link to the answer:https://stackoverflow.com/questions/4502633/how-to-affect-other-elements-when-one-element-is-hovered


## Author

- Frontend Mentor - [@Gloryjaw](https://www.frontendmentor.io/profile/Gloryjaw)



