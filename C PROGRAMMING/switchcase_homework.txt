/*To display the corresponding day according to the number entered by the user.
If the number entered is invalid, the loop runs to ask the user to re-enter the number.*/ 
#include<stdio.h>
int main()
{
    int n;
    while(1)
    {
    printf("Enter the number of the day: ");
    scanf("%d",&n);
    switch (n) 
    {
            case 1:
                printf("It is Monday\n");
                return 0;
            case 2:
                printf("It isTuesday\n");
                return 0;
            case 3:
                printf("It is Wednesday\n");
                return 0;
            case 4:
                printf("It is Thursday\n");
                return 0;
            case 5:
                printf("It is Friday\n");
                return 0;
            case 6:
                printf("It is Saturday\n");
                return 0;
            case 7:
                printf("It is Sunday\n");
                return 0;
            default:
                printf("Invalid input.\n");
        }
    }
    return 0;
}