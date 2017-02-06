# cheat sheet

if using jQuery, put all code in here:
  ```
  $(document).ready(function(){ 
  [all code here ] 
  });
  ```

on hover:

```cursor: pointer;```


## updating CSS with javascript and jQuery:

### Adding styles one by one:

  ```
  document.getElementById('hi').style["width"] = "100%";
  document.getElementById('hi').style.left = "5%";
 
  //hyphenation vs camelCase
  document.getElementById('hi').style['background-color'] = '#ccc'
  document.getElementById('hi').style.BackgroundColor = '#ccc'
  ```


  ```
  //cleaner - find element first
  var numOne = document.querySelector('.num-1')

  numOne.style.top = "5%";
  numOne.style.position = 'absolute';
  
  numOne.style['margin-top'] = "-35%";
  numOne.style['font-size'] = "4vh";

   ```
### replace element's ID or class entirely:
 ```
  topicBox.id = "box-1-open"
  //add a new class, dont forget the space
  topicBox.classList += " open"

  ```
  but if you're using jQuery, just use the techniques in [this codepen](http://codepen.io/evejweinberg/pen/oByXXQ)
  
  
# centering things
  
    ```
    left: 50%;
    transform: translateX(-50%);
    position: relative;
    ```
    
      
    

Sometimes you need more from the console:

```console.dir vs console.log```


  


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
