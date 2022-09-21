SET MYNUMBER TO 3
SEND "please guess number" TO DISPLAY
RECIEVE GUESS_NUMBER FROM KEYBOARD
IF GUESS_NUMBER > 10 THEN 
SEND "Too high your guess must be between 1 and 10" TO DISPLAY
ELSE IF GUESS_NUMBER = MYNUMBER THEN
SEND "Well done you guessed correctly" TO DISPLAY
ELSE SEND "Badluck the number is + MYNUMBER
