# JavaScript-Fundamentals

### part 1 :

1-2 == "2"; <br>**true**
2-2 === 2; <br>**true**
3-10 % 3; <br>**1**
4-10 % 3 === 1;<br>**true**
5-true && false; <br>**false**
6-false || true; <br>**true**
7-true || false; <br> **true**

<hr>

#### Part 2

1-<p>
var isLearning = true;<br>
if(isLearning){<br>
console.log("Keep it up!");<br>
} else {<br>
console.log("Pretty sure you are learning....");<br>
}</p><br>

 <p>  it print keep it up! coz isLearning true not false if false print else if</p>

2- Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own?<br> we can let the if statement turn the expression into a value that is true or false. True will evaluate into a truthy value<br>
 
 
   ```ruby
var firstVariable;
var secondVariable = "";
var thirdVariable = 1;
var secretMessage = "Shh!";

if(firstVariable){
    console.log("first");
} else if(firstVariable || secondVariable){
    console.log("second");
} else if(firstVariable || thirdVariable){
    console.log("third");
} else {
    console.log("fourth");
}
````

         <hr>
    
**What should the above code console.log? Why?<br>
   **third**
 **What is the value of firstVariable when it is initialized?<br>
 **The value of firstVariable is undefined. Variables that are not assigned to any value are assigned to the value undefined**
 **Is the value of firstVariable a "truthy" value? Why?<br> 
  No, undefined is a falsey value<br>
 **Is the value of secondVariable a "truthy" value? Why?<br>
 No, empty strings are falsey values as well <br>

 **Is the value of thirdVariable a "truthy" value? <br> 
 Yes, all numbers except for 0 are truthy 

  
   ### Part 3

 ```ruby
if(Math.random(20) > .5){
	console.log("Over 0.5");
} else {
	console.log("Under 0.5");
}
```
<hr> 

 #### JavaScript History and Setup
 #### Exercises
1-What is the difference between JavaScript and ECMAScript?<br>
ECMAScript is a standard. JavaScript is an implementation of that standard.<br>
2-Who is Brendan Eich?<br>
person who crated javascrint in 10 days <br>
3-How do you hide and show the Chrome console?<br>
ctrl+shift+j <br>
4-Create a simple page with a script tag. Inside of the script tag declare a couple of variables and then log their values to the console. <br>
5-Research prompt and confirm - what do they do? <br>