# Slot_Machine
Simulation of a slot machine that allows the user the deposit a balance in $(MAX:$100, MIN: $1).
  if the user inputs != int and/or not in the parameters the user is prompted again
Prompts the user on how many lines they'd like to bet on (MAX: 3 lines)
  -then how much money per line (Must be less than balance)  
Requires the user to press "enter" to play and "q" to cash out.
Once played, the random function is applied to the symbol count
  if the user gets three in a row, the code breaks and the user wins the amount based on the number of lines and $ put on each line * symbol value
  Otherwise, the user loses the set amount and is prompted to play again until balance = 0 or the player decides to cash out
