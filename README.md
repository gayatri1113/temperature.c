//# temperature.c//
#include<stdio.h>
int main()
{
    char city;
    float f,c;
    printf("Enter city name:");
    scanf("%s",&city);
    printf("Enter temperature in fahrenheit");
    scanf("%f",&f);
    c=(f-32)*5/9;
    printf("centigrade temperature=%f",c);
    return 0;
}
