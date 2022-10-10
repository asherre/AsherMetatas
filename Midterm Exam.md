SET 18-21 = perfect temperature
SEND 'Check Temperature' TO DISPLAY
RECEIVE 'Number' FROM KEYBOARD
IF 'Number = 18 - 21'
SEND 'Perfect' TO DISPLAY
ELSE IF 'Temperature < 18'
THEN SEND 'Cold,the perfect temperature should be 18-21' TO DISPLAY
ELSE IF 'Temperature > 21'
THEN SEND 'No, the perfect temperature should be 18-21' TO DIPSLAY
END
