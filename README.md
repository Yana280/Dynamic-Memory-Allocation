# Dynamic-Memory-Allocation
This program dynamically allocates memory for an integer array using malloc(), it
initializes its elements and prints them. 
It prompts the user to enter the number of elements required and checks if memory allocation is successful or not.
The returned pointer from malloc() is assigned to ptr, and the elements are initialized using a for loop. 
Finally, the array elements are printed using another for loop.
![Screenshot (301)](https://user-images.githubusercontent.com/125993593/234435868-8ea68240-4284-4bcd-b7ec-7f0a4712dab2.png)
## Algorithm
Start
Declare variables ptr, n, i.
Prompt user to enter the number of elements required for the array and store it in n.
Allocate memory for n integers using malloc() and assign the returned pointer to ptr.
Check if memory allocation was successful, and display an appropriate message.
If successful, initialize the array elements with values from 1 to n.
Print the elements of the array using a for loop.
Free the allocated memory using free().
Stop.
