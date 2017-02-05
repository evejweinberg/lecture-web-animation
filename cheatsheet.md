# cheat sheet

if using jQuery, put all code in here:
  ```
  $(document).ready(function(){ 
  [all code here ] 
  });
  ```

on hover:
```cursor: pointer;```


updating CSS on the fly:
3 options - 

  ```
  const numOne = document.querySelector('.num-1')

  numOne.style.top = "5%";
  numOne.style['margin-top'] = "-35%";
  numOne.style.position = 'absolute';
  numOne.style['font-size'] = "4vh";

  document.querySelector('#topic').style.opacity = "0";

  document.querySelector('.header').style.height = '5vh';
  topicBox.id = "box-1-open"
  topicBox.classList += " open"
  document.querySelector('.topic-list').style.display = 'block'

  ```
  
  
# centering things
  
    ```
    left: 50%;
    transform: translateX(-50%);
    ```
    
      
    

Sometimes you need more from the console:

```console.dir vs console.log```


  
  
## adding classes

[Example Pen of adding pre-written CSS classes] (http://codepen.io/evejweinberg/pen/oByXXQ?editors=1111)

Adding styles on the fly one by one:

  ```
  document.getElementById('hi').style["width"] = "100%";
  document.getElementById('hi').style.left = "5%";
 
  document.getElementById('hi').style['background-color'] = '#ccc'
  document.getElementById('hi').style.BackgroundColor = '#ccc'
  ```


// all children
```
.section3-pre > *
```


//input fields, remove annoying blue glow
```
input:focus {
    border: 1px black solid;
    outline: none;
}

```

background image fitting options:

[w3schools interactive site](http://www.w3schools.com/cssref/playit.asp?filename=playcss_background-size&preval=contain)
