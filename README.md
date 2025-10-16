int main() {
    float num1, num2, resultado; // Variáveis para os números e o resultado
    int opcao; // Opção escolhida pelo usuário

    // Entrada de dados
    printf("Digite o primeiro número: ");
    scanf("%f", &num1);

    printf("Digite o segundo número: ");
    scanf("%f", &num2);

    // Menu de operações
    printf("\nEscolha uma operação:\n");
    printf("1 - Adição\n");
    printf("2 - Subtração\n");
    printf("3 - Multiplicação\n");
    printf("4 - Divisão\n");
    printf("Opção: ");
    scanf("%d", &opcao);

    // Estrutura switch/case para decidir a operação
    switch (opcao) {
        case 1:
            resultado = num1 + num2;
            printf("\nResultado: %.2f + %.2f = %.2f\n", num1, num2, resultado);
            break;

        case 2:
            resultado = num1 - num2;
            printf("\nResultado: %.2f - %.2f = %.2f\n", num1, num2, resultado);
            break;

        case 3:
            resultado = num1 * num2;
            printf("\nResultado: %.2f * %.2f = %.2f\n", num1, num2, resultado);
            break;

        case 4:
            if (num2 != 0) {
                resultado = num1 / num2;
                printf("\nResultado: %.2f / %.2f = %.2f\n", num1, num2, resultado);
                
            } 
            
            //else {
              //  printf("\nErro: Divisão por zero não)
            //}


}



}
    
