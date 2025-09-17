## TESTE TITULO

### Subtitulo teste

- [link teste] (https://mail.google.com/mail/u/0/#inbox)
` Comentario`
```
#include <stdio.h>

int main() {
    // Declara um vetor de 10 posições
    int valores[10];
    int i;
    int maiorValor;

    // Pede ao usuário para digitar os 10 valores
    printf("Digite 10 valores inteiros:\n");
    for (i = 0; i < 10; i++) {
        printf("Valor %d: ", i + 1);
        scanf("%d", &valores[i]);
    }

    // Inicializa 'maiorValor' com o primeiro elemento do vetor
    maiorValor = valores[0];

    // Percorre o vetor a partir do segundo elemento para encontrar o maior valor
    for (i = 1; i < 10; i++) {
        if (valores[i] > maiorValor) {
            maiorValor = valores[i];
        }
    }

    // Exibe o maior valor encontrado
    printf("\nO maior valor no vetor e: %d\n", maiorValor);

    return 0;
}
```