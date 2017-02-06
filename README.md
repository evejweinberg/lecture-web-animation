# web animation with css, html, and javascript

## references
1. [Sing the movie website](http://www.singmovie.com/home)
2. [Spook] (http://www.rememberspook.com/#)
3. [Gemstones] (http://gemstones.elespacio.net/)
4. [thing] (http://www.basicagency.com/yir/)
5. [another cool editorial thing] (http://bergluft.hervis.at/chapter/1)
6. [another european site] (http://www.effektiv.fr/secteurs/ingenierie-management-de-production/)
7. [slight slide in on scroll](http://dagadam.com/)
8. [gooey menu] (http://codepen.io/evejweinberg/pen/RKJNXO)

Where to find more: [FWA Awards](https://thefwa.com/awards/) and [Awwwwwwards] (http://www.awwwards.com/)

## what we can learn today
1. [Powers of Ten sidebar] (http://itp.evejweinberg.com/powers_of_ten/)
  - [gist here] (https://gist.github.com/evejweinberg/716ef219c7c42bc465fb306d991a4362)
2. CSS Animation vs Transitions
  - [Example of animation] (http://codepen.io/havardob/pen/GZXOox)
  - [Example on hover shake](http://codepen.io/evejweinberg/pen/JEvaWr)
  - Transitions go from stateA to stateB; Animations can have multiple keyframes
3. How to read scss/sass on codepen
4. Using Chrome Dev Tools

- http://codepen.io/evejweinberg/pen/KaRrYj
- (to post) jQuery bottle shopping cart

## STACK:
1. css (then eventually SCSS/SASS)
2. javascript / jQuery
3. Chrome browser dev tools
4. Maybe Greensock if we have time
5. Flexbox for laying out divs, or bootstrap

[MY 'COMPREHENSIVE WEB ANIMATION' ARTICLE, FROM MEDIUM.COM] (https://medium.com/@evejweinberg/web-animation-everything-you-need-to-know-in-too-much-detail-91bf5d48f980#.t541ltp30)

## PROCESS. What does it feel like?:
1. watch tutorials (see medium article)
2. stackOverflow
  [sometimes not that helpful](http://stackoverflow.com/questions/8639383/how-do-i-center-an-svg-in-a-div)
3. Find things on codepen to Fork



## EX: stoke dash offset
[TweenLite from GSAP] (http://codepen.io/dewwwald/pen/pNOVLp)






# test and amend on browser

  1. open index in Chrome
  2. open console
  3. click on sources tab
  4. right click folder name for a dropdown
  5. select 'add to workspace'
  6. choose folder name
  7. right click on the css file
  8. choose Map to Network Resources
  9. choose css file from dropdown selection
  9. change css in the Source view
  10. save as you work! watch it update locally!



## So what is Sass and when should I use it?
As soon as you're writing css comfortably and you find yourself thinking, 'damn, I wish I could use variables!'. . start learning SASS. Until then, use css.

[installing sass](http://sass-lang.com/install)
[installing compass to compile sass to css](http://thesassway.com/beginner/getting-started-with-sass-and-compass)
```
$ sass --watch style.scss:style2.css
```



Sass is a version of CSS with more robust features. You can write in sass and then transpile to CSS when it's time to view your code. Sass can be written in two languages - sass or scss (sassy css). I use scss! It's easier bc it's more similar to CSS.

### SASS workflow
- Make a file called `style.scss` and write your styling there, using scss
- In the header of your html link to a normal .css file: `<link rel="stylesheet" href="css/style.css">`
- When you're done with your SCSS styling or just want to see the status of your page, use terminal to transpile
- before you can transpile, you must install the sass transpiler: https://www.jetbrains.com/help/webstorm/2016.3/transpiling-sass-less-and-scss-to-css.html#d253312e140
- in terminal `cd` into your directory and type $`





# Topics for next time:
- what about other browsers besides chrome?
- what about speed and performace issues css vs JS vs jQuery?






