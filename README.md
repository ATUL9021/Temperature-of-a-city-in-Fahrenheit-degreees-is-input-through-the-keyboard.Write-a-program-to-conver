# Temperature of a city in Fahrenheit degreees is input through the keyboard.Write a program to convert this temperature into centrigrade degrees

#include&lt;stdio.h>

int main()

{   

float fah,centigrade; 

printf("Enter temperature of Nagpur city in Fahrenheit\n"); 

scanf("%f",&amp;fah);   

centigrade=( fah- 32) *5/9; 


printf("After converting fahrenheit into centigrade the required centrigrade is %.3f",centigrade);

}


