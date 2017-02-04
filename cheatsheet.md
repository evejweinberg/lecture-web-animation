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
  // topicBox.style["width"] = "100%";
  // topicBox.style.height = "90%";
  // topicBox.style.top = "50%";
  // topicBox.style.left = "5%";
  // topicBox.style.transform = "translateY(-50%)";
  // topicBox.style['background-color'] = '#ccc'
  ```
  
  
# centering things
  
    ```
    left: 50%;
    transform: translateX(-50%);
    ```
    
      
    

Sometimes you need more from the console:

```console.dir vs console.log```

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

