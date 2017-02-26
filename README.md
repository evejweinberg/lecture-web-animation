
# web animation with css, html, and javascript

## references (get inspired)
1. [Sing the movie website](http://www.singmovie.com/home)
2. [Spook] (http://www.rememberspook.com/#)
3. [Gemstones] (http://gemstones.elespacio.net/)
4. [personal website] (http://eli.wtf/)
5. [cool editorial thing] (http://bergluft.hervis.at/chapter/1)
6. [another european site] (http://www.effektiv.fr/secteurs/ingenierie-management-de-production/)
7. [slight slide in on scroll](http://dagadam.com/)
7. [rad personal site] (http://alextade.me/)
8. [gooey menu] (http://codepen.io/evejweinberg/pen/RKJNXO)
9. [woah!](http://codepen.io/evejweinberg/pen/LxByzg)

Where to find more: [FWA Awards](https://thefwa.com/awards/) and [Awwwwwwards] (http://www.awwwards.com/) and [CSS Awards] (https://www.cssawards.net/)

## what we can learn today
2. CSS Animation vs Transitions
  - look at cheatsheet first
  - [Transition example](http://codepen.io/evejweinberg/pen/bgjWKp)
  - [Animation Keyframe example #1] (http://codepen.io/evejweinberg/pen/JEmogE)
  - [Animation Keyframe example #2](http://codepen.io/evejweinberg/pen/zNLVPe)
  - [Combo](http://codepen.io/evejweinberg/pen/JEvaWr)
  
2.  Switch to Chrome Dev tools and add clouds going across the screen


  
3. Adding CSS animation by using javascript: [Powers of Ten sidebar] (http://itp.evejweinberg.com/powers_of_ten/)
  - [gist here, using TweenLite] (https://gist.github.com/evejweinberg/716ef219c7c42bc465fb306d991a4362)
  - [codepen here, using CSS] (http://codepen.io/evejweinberg/pen/bgjRdq?editors=1111)
  
  
4.  [jQuery to change DOM elements](http://codepen.io/evejweinberg/pen/oByXXQ)
  
 
3. What else can we animate?
  - [All of these elements can be animated!](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties)



## STACK / WORKFLOW / TOOLS:
1. STACK: css (then eventually SCSS/SASS), javascript / jQuery, HTML
2. TOOLS: Text editor, codepen.io, Chrome browser dev tools
5. WORKFLOW: Watch tutorials (see medium article), read MDN, turn to stack over flow [sometimes a FAIL](http://stackoverflow.com/questions/8639383/how-do-i-center-an-svg-in-a-div), Find things on codepen to Fork

[MY 'COMPREHENSIVE WEB ANIMATION' ARTICLE, FROM MEDIUM.COM] (https://medium.com/@evejweinberg/web-animation-everything-you-need-to-know-in-too-much-detail-91bf5d48f980#.t541ltp30)




# code CSS live in Chrome

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


## Flexbox 
- [here](http://codepen.io/evejweinberg/pen/zNXeGj)

## So what is Sass and when should I use it?
As soon as you're writing css comfortably and you find yourself thinking, 'damn, I wish I could use variables!'. . start learning SASS. Until then, use css.

3. How to read scss/sass on codepen
  - [This one](http://codepen.io/evejweinberg/pen/WRKjzG)
  - [Flag] (https://codepen.io/saransh/pen/eBIov)


[installing sass](http://sass-lang.com/install)
[installing compass to compile sass to css](http://thesassway.com/beginner/getting-started-with-sass-and-compass)
```
$ sass --watch style.scss:style2.css
```
watch an entire folder:

```
$ sass --watch path/to/sass/folder:path/to/css/folder
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






