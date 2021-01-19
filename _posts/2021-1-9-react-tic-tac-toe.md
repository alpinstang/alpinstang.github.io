---
layout: post
title: Tic Tac Toe in React
---

This tutorial shows my approach to tic tac toe, and the problem of determining who won. The project is written in React. In this instance I instantiated the project using the ever-useful `create-react-app`.
For the purposes of this article I'll just point out the key parts of the app, but you can find the entire source code on [Github](https://github.com/alpinstang/tic-tac-react/).

All of this code is in the Board.jsx file. I plan to break out components more when I refactor the tic-tac-toe board to use `div`'s instead of `table` elements.

*Constructor:*
```js
  constructor(props) {
    super(props);

    this.myRef = React.createRef();

    this.state = {
      currentPlayer: "Player One",
      playerOne: [0, 0, 0, 0, 0, 0, 0, 0, 0],
      playerTwo: [0, 0, 0, 0, 0, 0, 0, 0, 0],
      count: 0,
      visible: false,
      winner: "Nobody",
    };
  }
```

You could simplify the state by determining the current player and winner by checking the count but I wrote it more explicitly during development.

*Check for a winning pattern:*
```js
checkForWinner = (arr, currentPlayer) => {
    console.log("Checking for winning pattern...");
    var array = [8, 3, 5, 7]; // just for testing. In production pass in the player's array.

    for (var i = 0; i < arr.length; i++) {
      for (var j = i + 1; j < arr.length; j++) {
        for (var k = j + 1; k < arr.length; k++) {
          if (arr[i] + arr[j] + arr[k] === 15) {
            console.log("Winner is " + currentPlayer);
            this.gameOver(currentPlayer);
            return [arr[i], arr[j], arr[k]];
          }
        }
      }
    }
    console.log("No winner.");
    return false;
  };
```

This is the workhorse of the component. It iterates over the array elements and checks if any three values add to 15. Why 15? Well this is using what is called a [magic square](http)
approach. You can learn more about the theory with the link, but the gist of it is any row, column, or diagonal of 3 (in our case) adds up to 15.

![magic square diagram](https://i.ytimg.com/vi/QHTe2gwXPiY/maxresdefault.jpg "Magic Square")

This eliminates the need for us to check specifically if three boxes have an 'X' or 'O' in them, as we just care about the unique number value of the box.
There are other ways that are arguably more efficient but this is a simple solution that doesn't put too much strain on the browser since we have such small arrays to check.

Here is the implemented page in React: [Tic Tac React Game](https://alpinstang.github.io/tic-tac-react/)

i would love to see your solution to this problem. Leave a comment or drop a link to your solution!

Happy Coding!
