 #include <stdio.h>

 int main(){

    int  b, c;

    printf("Enter values for addition\n");

    scanf("%d %d", &b, &c);

    int add = b + c;

    printf("Addition: %d\n", add);

    printf("Enter values for subtraction\n");

    int sub = b - c;

    scanf("%d %d", &c, &b);

    printf("Subtraction: %d\n", sub);

    printf("Enter values for multiplication\n");

    int multi = b * c;

    scanf("%d %d", &b, &c);

    printf("Multiplication: %d\n", multi);

    printf("Enter values for quotient\n");

    int quot =  b / c ;

    scanf("%d %d", &b, &c );

    printf("Quotient: %d\n", quot);

    printf("Enter values for reminder\n");

    int rem = b % c;

    scanf("%d %d", &b, &c);

    printf("Reminder: %d", rem);


    return 0;

}

