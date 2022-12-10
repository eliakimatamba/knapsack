# knapsack

    We've got a function that takes an integer n, the number of items in the array, and W, the width of each item.
    The function then creates an array ```K[n][W]``` where K is a one-dimensional array with n rows and W columns.
    For each row i, it sets all elements to 0 if i == 0 or w == 0 (the first two values).
    Otherwise it sets them to ```max(val[i - 1], val[i])``` for any value between ```wt[i - 1] <= w and wt[i]```.
    The code attempts to calculate the number of items in a knapsack, given the number of items and the size of the knapsack.
    The function "knapSack" takes three parameters: 1) The size of the knapsack, which is W; 2) The number of items to be placed into the knapsack, 
    which is n; and 3) The value for each item in the knapsack, which is val[].
    The function begins by initializing an array called K that will hold all possible combinations for a single item in a given position.
    For example, if there are two items in a given position (i.e., i = 0), then there will be
