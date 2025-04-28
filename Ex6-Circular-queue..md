# Ex6 Dequeue Elements from Circular Queue
## DATE: 3-03-25
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm


## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: C.Shrenidhi 
RegisterNumber: 212223040196 
*/

#include <stdio.h>
#define SIZE 5
int items[SIZE];
int front = -1, rear = -1;

int deQueue()
{
int element;
element=items[front];
if(isEmpty())
{
printf("Queue is Empty!!");
}
else
{
if(front==rear)
{
front=-1;
rear=-1;
}
else
{
}
front=(front+1)%SIZE;
}
return element
}

```

## Output:

<img width="489" alt="image" src="https://github.com/user-attachments/assets/0931936a-cf0c-44d7-a6f4-ec06762f6048" />




## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
