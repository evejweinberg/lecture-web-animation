# cheat sheet

CSS transition properties:
  ```
  transition: <property> <duration> <timing-function> <delay>;

  div {
    transition: all 5s ease-in 1s;
    
  }
  ```
 
CSS animation properties:
  ```
  parameters: name, duration, delay, iteration-count, direction, timing function.
  
  the order of the words do not matter, but numbers do. First number it finds will always be duration, 2nd number it finds will be delay.
  
  direction options: normal | reverse | alternate | alternate-reverse
  iteration count: interger or infinite; (not in quotes)
  timing-function: ease | linear | ease-in | ease-out | ease-in-out | step-start | step-end | steps( <integer> [, [ start | end ] ]? ) | cubic-bezier( <number>, <number>, <number>, <number> )
  
  div-to-animate{
    animation: wigglyJiggly 1s 2s 3 alternate backwards ease-in;
  }
  
  @keyframes wigglyJiggly {
  0% {
    font-size: 10px;
    left: 5%;
  }
  30% {
    font-size: 15px;
    left: 25%;
  }
  100% {
    font-size: 12px;
    left: 5%;
  }
}
  ```


## updating CSS with javascript (just use jQuery if you can!):

### Adding styles one by one:

 
    document.getElementById('hi').style["width"] = "100%";
    document.getElementById('hi').style.left = "5%";
 
  hyphenation vs camelCase
  
    document.getElementById('hi').style['background-color'] = '#ccc'
    document.getElementById('hi').style.BackgroundColor = '#ccc'
 


  
  cleaner - find element first
  
    var numOne = document.querySelector('.num-1')

    numOne.style.top = "5%";
    numOne.style.position = 'absolute';
  
    numOne.style['margin-top'] = "-35%";
    numOne.style['font-size'] = "4vh";

   
### replace element's ID or class entirely:

    topicBox.id = "box-1-open"
  
  add a new class, dont forget the space
    
      topicBox.classList += " open"


 Reminder! Just use jQuery instead - [this codepen has examples](http://codepen.io/evejweinberg/pen/oByXXQ)
  



if using jQuery, put all code in here:
  
    $(document).ready(function(){ 
    [all code here ] 
    });
  

# on hover, change curor to ![hand](https://i-msdn.sec.s-msft.com/dynimg/IC210310.png)

    
    cursor: pointer;

    .thingy:hover {
      cursor: pointer;
     }
     
     
     
# centering things
  
    .thing-to-center{
      left: 50%;
      transform: translateX(-50%);
      position: relative;
      }
    
    
      
# Sometimes you need more from the console (see html in other tab):

    console.dir vs console.log
    


# all children:

    .section3-pre > * {
      color: red;
    }



input fields, remove annoying blue glow:

    input:focus {
        border: 1px black solid;
        outline: none;
    }



# background image fitting options:

[w3schools interactive site](http://www.w3schools.com/cssref/playit.asp?filename=playcss_background-size&preval=contain)


# background gradient:
[codepen here](http://codepen.io/evejweinberg/pen/zNbRLV)

# most performative properties: opacity and transform

    '''
    text-transform: uppercase;
    '''
