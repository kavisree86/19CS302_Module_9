# EX 42 C program to write a fuctions to perform push,pop,display,peek in stack using array.
## DATE:
## AIM:
To write a fuctions to perform push,pop,display,peek in stack using array.

## Algorithm
Start.
Define a variables.
Write a functions to perform push,pop,display,peek in stack using array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.

## Program:
```
/*
C program to write a fuctions to perform push,pop,display,peek in stack using array.
Developed by: 
RegisterNumber:  
*/
```
```
int stack[100]; 
int size=3,top=-1,i; 
void push (float data) 
{ 
if(top==size-1) 
{ 
printf("stack is full\n"); 
} 
else{ 
top=top+1; 
stack[top]=data;} 
} void display(){ 
for(i=top; i>=0; i--){ 
printf("%d ",stack[i]); 
} 
if(top==-1) 
{ 
printf("stack is empty\n"); 
}
Void pop() 
{ 
if(top==-1) 
{ 
printf("stack is empty\n"); 
} 
else{ 
top=top-1; 
} 
} 
void peek() 
{ 
printf("%d ",stack[top]); 
}

```

## Output:
<img width="797" height="848" alt="image" src="https://github.com/user-attachments/assets/e78bd807-2711-44d7-b8e3-bb3629bddb82" />



## Result:
Thus the program was executed and the output was verified successfully.
