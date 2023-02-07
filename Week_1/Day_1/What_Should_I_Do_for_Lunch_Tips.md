### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


 ``` Javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("Not yet, got more work to do!"); 
  } else {
    if ((availableTime <= 30) && (availableTime >= 20)) {
      console.log("Time for food!");
    } else if (availableTime < 20) {
      console.log("Grab something quickly and eat in class.");
    } else if (availableTime > 30) {
      console.log("No Pain, no gain. Study more.");
    }
  }
}
```


