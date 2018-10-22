- [Week 1](/Week_1)
  - [Day 1](/Week_1/Day_1)

### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

````Javascript
 function whatToDoForLunch(hungry, availableTime) { if (!hungry) { console.log(`I'm not hungry and I have ${availableTime} minutes for lunch`); } else { if (availableTime >= 30) { console.log(`I'm hungry and I have ${availableTime} minutes for lunch`); } else if (availableTime >= 20) { console.log(`I'm hungry and I have ${availableTime} minutes for lunch.`); } else { console.log(`I'm hungry and I have ${availableTime} minutes for lunch`); } } } ```
````
