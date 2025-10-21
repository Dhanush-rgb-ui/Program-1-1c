#  Module-1 Day-3 SEB
## AIM:
To write a C program to calculate total, average and percentage of seven subjects.

## For example:
<img width="355" height="118" alt="image" src="https://github.com/user-attachments/assets/9b96d265-c951-427b-ac19-104907c232fa" />

## Program:
```c
#include <stdio.h>
int main()
{
    float a,b,c,d,e,f,g,tot,av,per;
    scanf("%f %f %f %f %f %f %f",&a,&b,&c,&d,&e,&f,&g);
    tot=a+b+c+d+e+f+g;
    av=tot/7;
    per=(tot/700)*100;
    printf("Total marks = %.2f\n",tot);
    printf("Average marks = %.2f\n",av);
    printf("Percentage = %.2f\n",per);
    return 0;    
}
```
## Result:
<img width="642" height="281" alt="image" src="https://github.com/user-attachments/assets/82aad3da-fea3-44b7-afe7-61df79f6170c" />

