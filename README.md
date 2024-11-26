Write a c program to calculate the compound interest 


#include<stdio.h>
#include<math.h>
void main()
{
    double principle_amount,rate,time,compound_interest,amount;
    int n;
    
    printf("enter the principle_amount\n :");
    scanf("%lf",&principle_amount);
    printf("enter the rate\n :");
    scanf("%lf",&rate);
    printf("enter the years of time \n:");
    scanf("%lf",&time);
    printf("enter the total amount of the compound_interest per year \n:");
    scanf("%d",&n);
    
    amount=principle_amount*pow((1+rate/100*n),n*time);
    compound_interest=amount-principle_amount;
    
    printf("compound_interest:%.2lf\n",compound_interest);
    printf("total_amount:%.2lf\n",amount);
}

=======================================================================================================================================================================================
output
enter the principle_amount
 :enter the rate
 :enter the years of time 
:enter the total amount of the compound_interest per year 
:compound_interest:3299.82
total_amount:4299.82


