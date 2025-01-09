The [countdown exercise from MDN](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Loops#active_learning_launch_countdown) has an annoying habit of freezing the page. This is an alternative that you can run locally in your browser to (hopefully) mitigate the issue.

To perform the exercise, edit [script.js](./script.js) and open (or refresh) [index.html](./index.html) in your browser to see the result. If you need to start over, copy over the content of [original.js](./original.js) to overwrite any changes you made. It should not be necessary to edit [index.html](./index.html) to complete the exercise.

To perform the next excersise (Guest List), go to the html and  replace this:  
```  
 <div class="output" style="height: 410px; overflow: auto"></div>
 ```
 with this:
 ```
 <div class="output" style="height: 100px;overflow: auto;">
  <p class="admitted">Admit: </p>
  <p class="refused">Refuse: </p>
</div>
```
Then, replace what is in the script.js file with this:


```const output = document.querySelector('.output');
output.textContent = "";

// let i = 10;

// const para = document.createElement('p');
// para.textContent = ;
// output.appendChild(para);
```


Then, save both files and continue like you did with the last one.