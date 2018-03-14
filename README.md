# Project-scheduling-non-preemptive
//This is the program
#include<bits/stdc++.h>
#define MAX 1000
struct Project
{
int PID;//ID OF THE PROCESS
int burst_time;//BURST TIME OF THE PARTICULAR
}
int main()
{
struct Project arr_process[MAX];
int i=1,c=0;
while(i>0)
{//opening of while
printf("ENTER THE PROCESS OF THE PROCESS\n");
scanf("%d"&arr_process[c].PID);//getting process id
printf("\nENTER THE BURST PROCESS OF THE PROCESS\n");
scanf("%d",&arr_process[c].burst_time); getting burst time of the process
c++;
printf("IF YOU WANT TO ENTER NEXT PROCESS THEN PRESS ANY KEY else 0");
int ch;
scanf("%d",&ch);
if(ch==0)
i--;
else;
i=1;
}//closing of while
}