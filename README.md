# C-examples

#the program that shows sum of two numbers

#include <stdio.h>
int main() {
   int num1;
   int num2;
   printf("please enter two numbers\n");
   scanf("%d,%d",&num1,&num2);
   printf("the numbers that you write are : %d,%d\n",num1,num2);
   int total=num1+num2;
   printf("total=%d",total);
   
}
#the program that computes area and environment of square

#include <stdio.h>
int main() {
    int edge;
	printf("please enter the value of edge\n");
	scanf("%d",&edge);
	int area;
	area=edge*edge;
	int environment;
	environment=4*edge;
	printf("area=%d",area);
	printf("\n");
	printf("environment=%d",environment);
}



#the program that computes area and environment of circle

#include <stdio.h>
int main() {
    int radius;
    printf("please enter the radius\n");
    scanf("%d",&radius);
    int pi=3.14;
    int area=4*pi*(radius*radius);
    int environment=2*pi*radius;
    printf("the area of circle:%d\n",area);
    printf("the environment of circle:%d",environment);
    
}
#include <stdio.h>

int main() {
    int num;
    
    printf("please enter a num\n");
    scanf("%d",&num);
    printf("%d\n",num);
    if (num%2==0){
        printf("the number is even");
    }
    else{
        printf("the number is odd");
    }
  
}
#include <stdio.h>

int main() {
    int distance;
    int hour;
	printf("please enter the distance\n");
	scanf("%d",&distance);
	printf("please enter the hour\n");
	scanf("%d",&hour);
	int speed;
	speed=distance/hour;
	printf("speed=%d",speed);
	
}

