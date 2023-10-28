#include<stdio.h>

main(){
    //writing a program to find leap year //
    int last_year_leapyear, current_year;
    printf("please mention the last year in which leapyear was there (eg_ 2004,):-");
    scanf("%d",&last_year_leapyear);
    printf("enter your current year here:-");
    scanf("%d",&current_year);


    int sum = 4 + last_year_leapyear;
    printf("your leap year is %d\n",sum);

    int left_years = sum - current_year ;

    if(sum == current_year){
        printf("this year is a leapyear\n");
    }
    else
    printf("there is %d years left .\n",left_years);






    



    
}
