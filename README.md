# logica-programacao-c

#include <stdio.h>

// 1. Declarando a constante PI
const float PI = 3.14159;

int main() {

    // 2. Declarando a variável do raio
    float raio;
    float area;

    // Pedindo o valor do raio
    printf("Digite o valor do raio: ");
    scanf("%f", &raio);

    // 3. Calculando a área
    area = PI * (raio * raio);

    // Mostrando os resultados
    printf("Raio: %.2f\n", raio);
    printf("Área do círculo: %.2f\n", area);

    return 0;
}
