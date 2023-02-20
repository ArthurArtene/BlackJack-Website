Blackjack game 

Professor: William Mongan
Students: Arthur Artene and Joshua Kallapati 

reasources: Professor Mongan for assitance and lecture notes on fintie state machines
https://stackoverflow.com/questions/2331086/how-to-access-element-whose-id-is-variable


What we both did: 
	We both focused on getting the script for the website to work in order to get the blackjack
	program to get running. Once the script and images were in place we can divide up the work
	properly. We also worked together to get a functional state machine. It would mainly be based
	on who wins and loses as well as if the game continues without either player quitting out. 
	Once we realize that we are dealing with mutiple conditions, we knew we were going to need
	the steps of the state machine to be put it into different sub functions in order to run the
	code faster and neater.

Arthur:
	I worked on the updateScore, clearArea, printCard, getNewCard, holding, checkHold, quit, clearArea. updateScore calculates the 	score for each player. clearArea clears the area and resets the game. printCard gets images from the array of images and prints it 	out to the proper area. getNewCard makes the game go and it activated upon pressing the button "HIT". holding is a function that is 	activated upon clicking the button "Hold". checkHold checks whether enough players held for the game to end.

Josh: 
	I specifically worked on generateImage, checkLossORWin, printResult, and start. These functions
	helped in creating the images that appear on the screen as well as mactching them to the correct
	values on the cardChecker and cardValue arrays. Function checkLossORWin helped figure out
	the state determined in printResult which arthur worked on. Besides that, I also worked on printing
	the cards out. 