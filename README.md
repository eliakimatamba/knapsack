# knapsack

We've got a function that takes an integer n, the number of items in the array,
and W, the width of each item.
The function then creates an array ```K[n][W]``` where K is a one-dimensional array
with n rows and W columns.
For each row i, it sets all elements to ```0 if i == 0 or w == 0``` (the first two values).
Otherwise it sets them to ```max(val[i - 1], val[i])``` for any value between ```wt[i - 1] <= w and wt[i]```.
The code attempts to calculate the number of items in a knapsack, given the number
of items and the size of the knapsack.
The function "knapSack" takes three parameters: 1) 
The size of the knapsack, which is W; 2)
The number of items to be placed into the knapsack, 
which is n; and 3) The value for each item in the knapsack, which is val[].
The function begins by initializing an array called K that will hold all possible combinations
for a single item in a given position.
The code in this example is used to calculate the maximum value of a list of numbers.
The code starts by checking to see if the first number in the list (in this case, 0) is greater
 than the second number in the list (in this case, 1).
If it is, then the first number is returned and nothing else happens.
If it isn't, then the second number is returned and everything else happens based on that value.
The knapSack() function takes four arguments: 1) The width of the sack ```(W), 2)``` The weight of each
item in pounds (```wt[i]), 3```) A list of values to be stored in memory ```(val[j]), and 4)``` 
The total number of items to be stored in memory (numItems).
The knapSack() function calculates a maximum value for each item in ```wt[]``` based on ```val[]``` and ```numItems```.
It does this by looping through all of the items in wt[] and comparing each one against 
val[] using a conditional statement.
If an item's value matches one from val[] then ```K[i][w]``` will contain that value.
Otherwise, ```K[i][w]```
The code will print the maximum value of an integer array, in this case W is 3 and val is 5.
