# [Assignment 4]

## Description

[COMP-1327]

## Author

[Anthony Gomes]

## Assignment

[This assignment involves troubleshooting an existing program to locate and correct logic errors. In addition, I will use exception handling to anticipate and handle potential exceptions which could lead to unexpected results and/or program crashes.]

## Code Modification

[I modified the code in the pixell_transaction_report.py program to handle any exception thrown if the input file cannot be located. I did this by using try and except blocks to look for errors and if any errors were found, I made it so that it would print a message saying which error it was.]

## Code Modification

[I collected the invalid records]

## Code Modification

[As a result of troubleshooting I found directly under the "# Update the customer's account balance based on the transaction type" that there was an "elif" instead of an "if" which was causesing the code to skip updating the customer's account balance based on the transaction type if it was the first instance of a customer's id showing up in the bank data.]

## Code Modification

[I found that "transaction counter" was redundant and I only needed transaction count.]

## Code Modification

[I had to write code so that the reader would skip the first line in the bank data file. it kept reading the names of the columns and registering them as invalid records. Those are just place holder names so and don't need to be read by the reader going through the bank data file.]

## Code Modification

[I fixed a typo in line 61 that said withdrawal instead of withdraw which was making the code skip over a chunk not allowing the calculation to be correct]
