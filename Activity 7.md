SET MystNumb = 3
SEND "Please type a number" TO DISPLAY
RECEIVE 11 FROM KEYBOARD
IF Guess_Nuumber > 10 THEN
SEND "Number too high, must be lower than 10" TO DISPLAY
ELSE
IF Guess_Number < MystNumber THEN
SEND "Number too low, try next time" TO DISPLAY
ELSE
IF Guess_Number = Number  THEN
SEND "Number is correct"
END
