cheat sheet

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



`console.dir vs console.log`
