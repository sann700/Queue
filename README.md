# Queue
#include<stdio.h>
#define MAX 10
int QUE[MAX],Front=-1,Rear=-1;
void enqueue(int a)
{
  if(rear==MAX-1)
  printf("\nQueue overflow");
  else
  {
     Rear+=1;
     QUE[Rear]=a;
     if(Front==-1)
     Front=0;
     }
     }
     int main()
     {  int item;
        printf("\nEnter the element to be inserted");
        scanf("%d",&item);
        enqueue(item);
        }
