#include<stdio.h>
#include<math.h>
float growthrate(floatinitial,floatfinal,floattime)
{
return(final-initial)/time;
}
int main()
{
float initialpop,finalpop,time,rate;
printf("enter initial population:");
scanf("%f",&initialpop);
printf("enter final population:");
scanf("%f",&finalpop);
printf("enter time:");
scanf("%f",&time);
//function call
rate=growthrate(initialpop,finalpop,time);
printf("growhrate=%.2f",rate);
return 0;
}

