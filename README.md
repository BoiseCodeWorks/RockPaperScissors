RockPaperScissors
=================
We are going to create the classic game Rock Paper Scissors.

User Interface
--------------
Start by creating a user interface for the game.  

The interface can look however you want it to. It might be a good idea
to look at examples of the `panel` component in the bootstrap documentation.

The interface should be simple and must contain at least 3 buttons: Rock, Paper, and Scissors.

When a button is pressed, the game should execute a function written in javascript.
Us the `onclick` attribute to execute the function. The rock button might look like this.
```html
<button onclick="play('rock')">Rock</button>
```

Javascript
-----------
The following code should be written in the app.js file.

### The Play Function
Begin by creating a function named `play`.

The function should accept a single argument that represent the players choice: "rock" "paper" or "scissors".
A good name for the argument might be `playerChoice`.

Inside the function we will need to create a variable to hold the value for the computer's choice.
For now, assign the value of computer's choice to "rock".

### Determine a Winner!
We are now going to add logic to the `play function` that will determine who wins the game. 
This will require a you to use `if` `else` statements.

 **TIP:** Before writing code, it may be beneficial to write down on a scrap of paper the logic that will be used 
 to determine a winner. Writing in plain english before writing in code is a good idea!!!

```javascript

var x = ?;

if(x === 5){
	//x is equal to 5
} else if(x > 4){
	//x is not equal to 5, but is greater than 4
} else if(x < 2){
	//x is not equal to 5, not greater than 4, but is less than 2.
} else{
	//x is not equal to 5, not greater than 4, and not less than 2.
}


//it is also possible to nest if statements
if(x > 5){
	//x is greater than 5
	if(x < 7 ){
		//X is between 5 and 7.
	}else{
		//x is greater than 7
	}
}
```

When a winner is found, let the user know. You can do so by displaying an alert with a message...
`google javascript alert`;

For bonus points, you may want to try writing a message back to the user interface. But I will let you
try that one on your own. Hint... `document.getElementById()` and `.textContent`


# Good Luck! 
