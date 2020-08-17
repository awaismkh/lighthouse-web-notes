### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
let whatToDoForLunch = function(hungry,availableTime) {
  if (hungry && availableTime < 20) {
    console.log('pick something and eat in the back with fellow classmates');
  } else if (hungry && (availableTime >= 20 && availableTime <= 30)) {
    console.log('You deserve a break, go to Gastown');
  } else if (hungry && availableTime > 30) {
    console.log('this is a bootcamp, reconsider');
  } else {
    console.log('just work if you\'re not hungry');
  }

};

console.log(whatToDoForLunch(true, 21));
````
