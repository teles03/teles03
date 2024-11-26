#include <stdio.h>

int main() {
    int resposta; // Variável para armazenar a resposta do usuário

    printf("Me perdoa por ser um Otário: Sim ou Não? (1 para Sim, 0 para Não)\n");
    scanf("%d", &resposta);

    // Validação da entrada
    if (resposta != 0 && resposta != 1) {
        printf("Resposta inválida. Por favor, digite 1 para Sim ou 0 para Não.\n");
        return 1; // Indica erro
    }

    if (resposta == 1) {
        printf("Desculpa msm, vc nao merece nada disso.\n");
    } else {
        printf("[ERRO]:pode ser que eu tenha feito algo errado, mas saiba que eu te amo e ate no meio desses 0's e 1's eu ainda tenho medo de te ver assim.\n");
    }

    return 0;
}
