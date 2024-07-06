#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

void main() {
    setlocale(LC_ALL, "");

    float valor1, valor2;
    int opcao;

    while(opcao < 1 || opcao > 4){
    printf("Digite o valor 1: ");
    scanf("%f", &valor1);
    printf("Digite o valor 2: ");
    scanf("%f", &valor2);

    printf("\n\nDigite:");
    printf("\n1 - Para Somar");
    printf("\n2 - Para Subtrair");
    printf("\n3 - Para Multiplicar");
    printf("\n4 - Para Dividir\n");
    scanf("%d", &opcao);

    switch (opcao) {
        case 1:
            printf("\nA soma é = %.2f", valor1 + valor2);
            break;
        case 2:
            printf("\nA subtração é = %.2f", valor1 - valor2);
            break;
        case 3:
            printf("\nA multiplicação é = %.2f", valor1 * valor2);
            break;
        case 4:
            if (valor2 == 0) {
                printf("Erro: divisão por zero não permitida.");
            } else {
                printf("\nA divisão é = %.2f", valor1 / valor2);
            }
            break;
        default:
            printf("Opção inválida\n\n");
            break;
}
    }
   printf("\n\n");
   system("pause");
}
