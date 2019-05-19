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

#include <stdio.h>

int main() {
    int num1,num2;
    printf("please enter the first number\n");
    scanf("%d",&num1);
    printf("please enter the second number\n");
    scanf("%d",&num2);
    printf("first num:%d\nsecond num:%d\n",num1,num2);
    if(num1>num2){
        printf("first number is greater than second number");
        
    }else if(num1==num2){
        printf("numbers that you enter are equal each other");
        
    }else{
        printf("second number is greater than first number");
    }
    
	
}
#include <stdio.h>
#include <math.h>

int main() {
	int x1,x2;
	int y1,y2;
    float distance;
	printf("please enter the coordination (x1,y1)\n");
	scanf("%d,%d",&x1,&y1);
	
    printf("please enter the coordination (x2,y2)\n");
	scanf("%d,%d",&x2,&y2);
	
	distance=sqrt(pow((x2-x1),2)+pow((y2-y1),2));
	printf("%f",distance);
	
}

#include <stdio.h>

int main() {
	int num=0;
	int i=0;
	printf("please enter the number ");
	printf("\n");
	scanf("%i",&num);
	for(i=1;i<10;i++){
	    printf("%i ",num*i);
	    
	}
	

	
}

#include <stdio.h>

int main() {
    int num;
	int i=0;
	int fact=1;
	printf("please enter the number: ");
	scanf("%i",&num);
	printf("%i",num);
	printf("\n");
	for(i=1;i<=num;i++){
	    if(num==0||num==1){
	        fact=1;
	    }else{
	        fact=fact*i;
	    }
	}
	printf("factorial of the number is: %i\n",fact);
	
}
#include <stdio.h>
#include <math.h>

int main() {
    int num;
    int exp;
	
	printf("please enter the number: ");
	scanf("%i",&num);
	printf("%i",num);
	printf("\n");
	
	printf("please enter the exp: ");
	scanf("%i",&exp);
	printf("%i",exp);
	printf("\n");
	
	
	int power;
	power=int(pow(num,exp));
	printf("%i",power);
	
	
    

}




