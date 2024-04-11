# Reorganize-String
Rearrangement of the characters of string so that any two adjacent characters are not the same.
#### Approach
-This code implements a solution to reorganize a string such that no two adjacent characters are the same. 

-It uses a priority queue to store characters along with their frequencies. 

-It iterates through the input string to count character frequencies and inserts them into the priority queue. 

-Then, it repeatedly pops two characters with the highest frequencies from the queue, appends them 
to the answer string, decrements their counts, and pushes them back if their count is still positive. 

-If there's only one character left in the queue at the end, it checks if its count is zero 
and appends it to the answer if so otherwise, it returns an empty string indicating impossibility.

-Finally, it returns the reorganized string or an empty string if reorganization is not possible.
