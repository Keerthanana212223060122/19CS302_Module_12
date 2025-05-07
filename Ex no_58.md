# EX 58 C Function to display queue elements using Linked List.(use float data in the queue)
## DATE:07-05-2025
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm:

1. **Start**  
2. Define a structure `Node` with two fields:  
   - `data` (integer type)  
   - `next` (pointer to the next node)  
3. Initialize `front` and `rear` pointers:  
   - `front` points to the first node in the queue  
   - `rear` points to the last node in the queue  
4. Check if `front` is `NULL`:  
   - If `NULL`, print "Queue is empty" and exit.  
5. Otherwise, create a temporary pointer `temp` pointing to `front`.  
6. Loop through the queue:  
   - Print `temp->data`.  
   - Move `temp` to `temp->next`.  
7. Continue until `temp` becomes `NULL`.  
8. **End**  

This algorithm efficiently traverses and prints all queue elements using a linked list. Want a full implementation with enqueue and dequeue functions? 🚀


## Program:
```c program
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void display()
{
    struct Node *ptr;
    ptr=front;
    if(front==NULL)
    {
        printf("queue is empty");
        
    }
    else
    {printf("Queue elements:\n");
    while(ptr!=0)
    {
        printf("%.3f\n",ptr->data);
        ptr=ptr->next;
    }}
}
```

## Output:
![image](https://github.com/user-attachments/assets/b8dfe2ca-8868-454c-ae0b-769a11eeeaff)



## Result:
Thus the program was executed and the output was verified successfully.
