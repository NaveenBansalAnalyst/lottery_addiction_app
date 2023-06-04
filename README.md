# lottery_addiction_app
In the 6/49 lottery, six numbers are drawn from a set of 49 numbers that range from 1 to 49. A player wins the big prize if the six numbers on their tickets match all the six numbers drawn. If a player has a ticket with the numbers {13, 22, 24, 27, 42, 44}, he only wins the big prize if the numbers drawn are {13, 22, 24, 27, 42, 44}(does NOT need to be in that order). If only one number differs, he doesn't win.

The main thing to consider about lottery drawings is they are Unordered sampling without replacement.

We made four important functions that can be embeded into the app which will allow the users to calculate their chances of winning in each respect. These functions are:

Function to calculate probability for a single ticket - Allows the user to calculate the probability of winning the big prize(always outputs the same answer).

Function to match numbers with historical draws - Allows the user to compare their numbers with historical draws (from Canada) and see if their chosen number has ever won the lottery.

Function for multi-ticket probability - Allows the user to check the probability of winning the big prize if they buy more than one ticket.

Function for Less winning numbers - Allows the user to know the probability of winning less than 6 numbers.
