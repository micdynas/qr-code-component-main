# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### Screenshot

![](Screenshot%20(1).png)

![](Screenshot%20(3).png)





### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap


### What I learned

 I learnt how to integrate bootsrap into my code to ensure responsiveness of the body, it was a little difficult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

But i believe i did a good job with the things i used. Always open to constructive critism on how to get better.


```css
body{
 padding-top: 100px;
 display: flex;
 justify-content: center;
  align-items: center;
}

.card{
    width: 16rem;
    height: 27rem;
    border-radius: 15px;
     display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: 5px 5px 5px  rgb(212, 210, 210);
    
}
.card-img-top{
    
    border-radius: 10px;
    width: 14rem;
    height: 14rem;
    margin: 15px 0;

}

.card-body{
    text-align: center;
}

.card-title{
    font-size: large;
    font-weight: bold;
   padding-bottom: 10px;
}

.card-text{
    font-size: small;
    font-weight: 400;
    color: grey;
}
```


### Continued development
I would to continue focusing on how to reduce the quantity of my css code while improving its 
efficiency.
And I would also like to make my own QR Generator so this could be used as a default template.


### Useful resources

- (https://getbootstrap.com/docs/5.3/components/card/)- At some point i got stuck on how to implement the card component in bootstrap and this helped



## Author
- Frontend Mentor - @micdynas

