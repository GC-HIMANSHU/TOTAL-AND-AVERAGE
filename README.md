# TOTAL-AND-AVERAGE
<br>
#include<stdio.h>
int main(){
	int a,b,c,d;
	float e,f;
	printf("\nMarks Of Chemistry:");
	scanf("%d",&a);
	printf("\nMarks Of Maths:");
	scanf("%d",&b);
	printf("\nMarks Of Biology:");
	scanf("%d",&c);
	printf("\nMarks Of Physics:");
	scanf("%d",&d);
	e=a+b+c+d;
	f=e/4;
	printf("\nTotal Marks =%f" ,e);
	printf("\nAverage Marks =%f" ,f);
	return 0;
}
