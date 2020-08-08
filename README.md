#include <stdio.h>

int main()
{
    int i;
    int NumberOfGrades;
    double b;
   double c;
    double d;
    
    printf("How many grades do you want to get the average of: ");
    scanf("%d",&NumberOfGrades);
    
    for(i=0;i<NumberOfGrades;i++){
        puts("Enter grade Number");
        scanf("%lf",&b);
        
       c= c+b; 
    }
d = (c/NumberOfGrades);
puts("The average is:");
printf("%.5lf",d);
    return 0;
}
