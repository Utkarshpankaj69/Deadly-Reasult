#include<stdio.h>
int main()
{
float a, b, c, d, e;
float avarage, total, percentage;

printf("Write marks of all subject: \n");
scanf("%f%f%f%f%f", &a, &b, &c, &d, &e);

total=a+b+c+d+e;
avarage=total / 5;
percentage= (total / 500)*100;

printf("Your total marks: %f \n", total);
printf("Your avarage marks: %f \n", avarage);
printf("Your percentage marks: %f \n", percentage);
scanf("%f",percentage );

if(percentage>=90){
printf("A1 GRADE");
}
else if(percentage>=80){
printf("A1 GRADE");
}
else if(percentage>=90){
printf("A2 GRADE");
}
else if(percentage>=70){
printf("B1 GRADE");
}
else if(percentage>=60){
printf("B2 GRADE");
}
else if(percentage>=50){
printf("C1 GRADE");
}
else if(percentage>=40){
printf("C2 GRADE");
}

else{
printf("Fail");
}

return 0;



}
