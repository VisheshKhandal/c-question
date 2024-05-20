# c-question
question 1 -- check

#include<stdio.h>

int main() {
    int length,breath;
    printf("Enter the length of the rectangle:"); 
    scanf("%d", &length);

    printf("The breath of the rectangle is:" );
    scanf("%d", &breath); 

    printf("the area of rectangle is %d", length*breath);  

    return 0;
}
question 2 -- check

#include<stdio.h>

int main() {
    int radius;
    float pi =3.14;
    printf("Enter the radius of the circle:"); 
    scanf("%d", &radius);

    printf("the area of circle is %f", pi*radius*radius);
    return 0;
}
question 3 -- check

#include<stdio.h>

int main() {
    float celsius,far;
    printf("Enter the celsius temprature  is :");
    scanf("%f", &celsius);
    far = (celsius * 9.0 / 5.0) + 32;
    printf("the temprature of celsius to farenhite is %f" , far );
    return 0;
}
 
question 4 -- check

#include<stdio.h>

int main() {
    int principal,rate,years;
    printf("Enter the principal value : ");
    scanf("%d", &principal);

    printf("Enter the rate value : ");
    scanf("%d", &rate);

    printf("Enter the years value : ");
    scanf("%d", &years);

    printf("the vale of simple intrest is %d ", (principal * rate * years)/100);

    return 0;
}


// Question 5 -- check { FIXME: ENCRYPT FUNCTION }
//dpnf!up!uif!ipnf!boe!hp!up!txjnnjoh
// #include<stdio.h>
// void encrypt(char *c){
//     char *ptr = c;
//     while(*ptr!= '\0'){
//         *ptr = *ptr + 1;
//         ptr++;
//     }   
// }
// int main() {
//     char c[] = "come to the home and go to swimming";
//     encrypt(c);
//     printf(" encrypted string is :%s", c);
//     return 0;
// }
//  Question 5 -- check { FIXME: DECRYPT FUNCTION }
#include<stdio.h>
void decrypt(char *c){
    char *ptr = c;
    while(*ptr!= '\0'){
        *ptr = *ptr - 1;
        ptr++;
    }   
}
int main() {
    char c[] = " dpnf!up!uif!ipnf!boe!hp!up!txjnnjoh";
    decrypt(c);
    printf(" decrypted string is :%s", c);
    return 0;
}
// question 1 -->>... check 

// #include<stdio.h>

// int main() {
//     int physics,chemistry,math,english,hindi;
//     float total;

//     printf("enter your physics marks\n");
//     scanf("%d",&physics); 

//     printf("enter your chemistry marks\n"); 
//     scanf("%d",&chemistry);

//     printf("enter your math marks\n");
//     scanf("%d",&math);
    
//     printf("enter your english marks\n");
//     scanf("%d",&english);

//     printf("enter your hindi marks\n");
//     scanf("%d",&hindi);

//     total = (physics+chemistry+math+english+hindi) / 5;
    
//     if((total<40) || physics < 33 || chemistry < 33 ||math < 33 ||english < 33 || hindi < 33) 
//     {
//         printf(" your total percentage is %f and you are fail",total );
//     }
//     else{
//         printf(" your total percentage is %f and you are pass",total );
//     }
//     return 0;
// }

// question 2 -->>... check

// #include<stdio.h>

// int main() {
//     int a,b,c,d;
//     printf("enter the value of a\n");
//     scanf("%d",&a);

//     printf("enter the value of b\n");
//     scanf("%d",&b);

//     printf("enter the value of c\n");
//     scanf("%d",&c);

//     printf("enter the value of d\n");
//     scanf("%d",&d);

//     if(a>b && a>c && a>d)
//     {
//         printf("a is greater");
//     }
//     else if(b>a && b>c && b>d)
//     {
//         printf("b is greater");
//     }
//     else if(c>a && c>b && c>d)
//     {
//         printf("c is greater");
//     }
//     else if(d>a && d>b && d>c)
//     {
//         printf("d is greater");
//     }   
//     return 0;
// }   

// question 3 -->>... check (ASCII Values)

// #include<stdio.h>

// int main() {
//     char ch;
//     printf("enter the charachter\n");
//     scanf("%c",&ch);

//     if(ch<=122 && ch>=97)
//     {
//         printf("it is lower case ");
//     } 
//     else{
//         printf("it is upper case ");    
//     }  
//     return 0;
// }

// question 4 -->>... check
// #include<stdio.h>
// float force( float mass);
// int main() {
//     float m;
//     printf("enter the value of mass\n");    
//     scanf("%f",&m);
//     printf(" the value of force is %.2f",force(m)); 
//     return 0;
// }

//     float force( float mass)   
//     {
//         float result = mass * 9.8;
//         return result;
//     }   

// question 5 -->>... check
// #include <stdio.h>

// int fibonacci(int n) {
//   if (n < 0) {
//     printf("Error: Fibonacci sequence is not defined for negative numbers.\n");
//     return -1; // Indicate an error
//   } else if (n <= 1) {
//     return n; // Base cases: fibonacci(0) = 0, fibonacci(1) = 1
//   } else {
//     return fibonacci(n - 1) + fibonacci(n - 2); // Recursive calls
//   }
// }

// int main() {
//   int n;

//   printf("Enter a non-negative integer for the Fibonacci sequence: ");
//   scanf("%d", &n);

//   int result = fibonacci(n);

//   if (result != -1) {
//     printf("The %dth number in the Fibonacci sequence is %d\n", n, result);
//   }

//   return 0;
// }

// question 6 -->>... check

// #include<stdio.h> 
// void multiplyByten (int *num) {
//     *num *= 20; 
// }
// int main() {
//     int num;

//     printf("enter the num : \n");
//     scanf("%d",&num);
//     printf("the current value is %d",num);
//     multiplyByten(&num);
//     printf("the new value is %d",num);
//     return 0;
// }   
 
// question 7 -->>... check

