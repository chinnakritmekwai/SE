# SE
#include<stdio.h>
int  main(  )
{
    int score;
    scanf("%d",&score);
    if(score>100) 
       	printf("Error"); 
    else if(score>=80) 
       	printf("Grade 4"); 
    else if(score>=75)
       	printf("Grade  3.5");
    else if(score>=70)
       	printf("Grade  3");
    else if(score>=65)
       	printf("Grade  2.5");
    else if(score>=60)
       	printf("Grade  2");
    else if(score>=55)
       	printf("Grade  1.5");
    else if(score>=50)
       	printf("Grade  1");
}
