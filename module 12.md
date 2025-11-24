
# EXP NO 26: C PROGRAM TO DISPLAY STACK ELEMENTS USING LINKED LIST.
## Aim:
To write a C program to display stack elements using linked list.

## Algorithm:
1.	Define a structure Node with two members: data to store the integer value and next to point to the next node in the linked list.
2.	Declare a global variable head representing the starting node of the linked list.
3.	Define a function display to print the elements of the linked list.
4.	Declare a pointer p and initialize it with the head of the linked list.
5.	Use a while loop to traverse the linked list:
6.	Print the data of the current node.
7.	Move to the next node using the next pointer.
 
## Program:
```c
int stack[100],top,i;
void display()
{
    for(int i=top;i>=0;i--)
    {
        printf("%d->",stack[i]);
    }
}
```

## Output:

<img width="541" height="537" alt="image" src="https://github.com/user-attachments/assets/d9a50d43-1da7-4e8e-9b5d-247c257d7ca6" />

## Result:
Thus, the program to display stack elements using linked list is verified successfully. 

# EXP.NO 27: C PROGRAM TO POP AN ELEMENT FROM THE GIVEN STACK USING LINKED LIST.
## Aim:
To write a C program to pop an element from the given stack using liked list.
## Algorithm:
1.	Check for Empty Stack
2.	If head is equal to NULL, Print "Stack is empty."
3.	Else Proceed to the next step.
4.	Set head to point to the next node in the stack. 
## Program:
```c
float stack[100];
int top;
void pop ()
{
    if(top!=-1)
    {
        top--;
    }
}
```
## Output:

<img width="585" height="723" alt="image" src="https://github.com/user-attachments/assets/4fe58a2c-eeca-4691-abfc-d17e2f479004" />

## Result:
Thus, the program to pop an element from the given stack using liked list is verified successfully.
 
# EXP NO:28 C PROGRAM TO DISPLAY QUEUE ELEMENTS USING LINKED LIST.
## Aim:
To write a C program to display queue elements using linked list.
## Algorithm:
1.	Check if Queue is Empty
2.	Display Queue Elements
3.	Print the data of the current node pointed to by front
4.	Update front to point to the next node.
5.	End the display function.
 
## Program:
```c
char queue[50];
int front,rear;
void display()
{
    if(front==-1 && rear==-1)
    {
        printf("No elements to display");
    }
    else
    {
        for(int i=front;i<=rear;i++)
        {
            printf("%c\n",queue[i]);
        }
    }
}
```
## Output:

<img width="693" height="525" alt="image" src="https://github.com/user-attachments/assets/0a233381-8235-4010-a563-d24ce7b7f2ff" />

## Result:
Thus, the program to display queue elements using linked list is verified successfully.
 
# EXP NO:29 C PROGRAM TO INSERT ELEMENTS IN QUEUE USING LINKED LIST
## Aim:
To write a C program to insert elements in queue using linked list
## Algorithm:
1.	Allocate Memory for New Node
2.	Set Data and Next Pointer
3.	Check if Queue is Empty
4.	Set both front and rear to point to the new node p.
5.	Set the next pointer of the current rear to point to the new node p.
6.	End of Enqueue Operation
 
## Program:
```c
float queue[50];
int size=10;
int front,rear;
void enqueue(float data)
{
    if(rear>=size)
    {
        printf("Queue Overflow");
    }
    else if(front==-1&&rear==-1)
    {
        rear=front=0;
        queue[rear]=data;
    }
    else
    {
        rear++;
        queue[rear]=data;    
    }
}
```
## Output:

<img width="745" height="463" alt="image" src="https://github.com/user-attachments/assets/b34f8c24-04b4-4d04-81c7-c3e8d948dde6" />
## Result:
Thus, the program to insert elements in queue using linked list is verified successfully.

# EXP NO:30 C FUNCTION TO FIND THE PEEK OF QUEUE USING LINKED LIST.
## Aim:
The aim of this function is to retrieve the "peek" (the front element) of a queue implemented using a linked list
## Algorithm:
1.	Check if the queue is empty:
o	If the queue is empty (i.e., the front pointer is NULL), return an error or a message indicating that the queue is empty.
2.	Access the front element:
o	If the queue is not empty, return the data stored in the front node of the linked list (i.e., the element at the head of the queue).
## Program:
```c
char queue[50];
int front,rear;
void peek()
{
    printf("%c",queue[front]);
}
```
## Output:

<img width="523" height="479" alt="image" src="https://github.com/user-attachments/assets/a44879af-a4da-4d5c-9fbe-f7f9aad59cae" />

## Result:
Thus, the program to retrieve the "peek" (the front element) of a queue implemented using a linked list is verified successfully.


