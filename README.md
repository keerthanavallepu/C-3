# include <stdio.h>
int main(){
float length,width,area;
printf("enter the value of length:");
scanf("%f",& length);
printf("enter the value of width:");
scanf("%f",&width);
area = length * width;
printf("Area of a rectangle=%2f square units/n",area);
return 0;
}
