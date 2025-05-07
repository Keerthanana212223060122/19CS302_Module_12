# EX 56 A function to display stack elements using Linked List.(store float data in stack) .
## DATE:07-05-2025
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm:
1. Start. 
2. Define a variables. 
3. Write a program to display stack elements using linked list. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 
## Program:
```c program
Struct Node 
{ 
float data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *temp= head; 
while(temp!=NULL) 
{ 
printf("%.2f\n",temp->data); 
temp=temp->next; 
} 
 
}
```
## Output:

![image](https://github.com/user-attachments/assets/febd2b64-c8eb-4dda-bc3a-ad746a67ac5b)


## Result:
Thus the program was executed and the output was verified successfully.
