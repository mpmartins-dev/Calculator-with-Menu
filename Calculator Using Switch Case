#include <stdio.h>
#include <stdlib.h>

void main() {

    float value1, value2;
    int option;

    while(option < 1 || option > 4){
    printf("Enter the value 1: ");
    scanf("%f", &value1);
    printf("Enter the value 2: ");
    scanf("%f", &value2);

    printf("\n\nPress:");
    printf("\n1 - Sum");
    printf("\n2 - Subtract");
    printf("\n3 - Multiply");
    printf("\n4 - Divide\n");
    scanf("%d", &option);

    switch (option) {
        case 1:
            printf("\nThe sum is = %.2f", value1 + value2);
            break;
        case 2:
            printf("\nThe subtraction is = %.2f", value1 - value2);
            break;
        case 3:
            printf("\nThe multiplication = %.2f", value1 * value2);
            break;
        case 4:
            if (value2 == 0) {
                printf("Error: division by zero not allowed.");
            } else {
                printf("\nThe division is = %.2f", value1 / value2);
            }
            break;
        default:
            printf("Invalid\n\n");
            break;
}
    }
   printf("\n\n");
   system ("pause");
}

