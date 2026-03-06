# Atividade-Termometro
#Impressão de Números de 1 a N: 
#include <stdio.h>

int main() {
    int N;
    int i;
    
    scanf("%d", &N);
    
    for (i = 1; i <= N; i++) {
        printf("%d\n", i);
    }
    
    return 0;
}

#Cálculo de Fatorial:
#include <stdio.h>

int main() {
    int n;
    long long fatorial = 1;
    int i;
    
    scanf("%d", &n);
    
    for (i = 1; i <= n; i++) {
        fatorial *= i;
    }
    
    printf("%lld\n", fatorial);
    
    return 0;
}

#Soma de Números em um Array:
#include <stdio.h>

int main() {
    int numeros[5];
    int soma = 0;
    int i;
    
    for (i = 0; i < 5; i++) {
        scanf("%d", &numeros[i]);
        soma += numeros[i];
    }
    
    printf("%d\n", soma);
    
    return 0;
}

#conversão de temperatura: 
#include <stdio.h>

int main() {
    int opcao;
    double celsius, fahrenheit;

    scanf("%d", &opcao);

    if (opcao == 1) {
        scanf("%lf", &celsius);
        fahrenheit = (celsius * 9.0 / 5.0) + 32.0;
        printf("%.2f\n", fahrenheit);
    } else if (opcao == 2) {
        scanf("%lf", &fahrenheit);
        celsius = (fahrenheit - 32.0) * 5.0 / 9.0;
        printf("%.2f\n", celsius);
    }

    return 0;
}
