#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int tentativas;
    int palpite;
    char resp;

    srand(time(NULL));

    do {
        tentativas = 0;  

        int numaleatorio = rand() % 16 + 1;

        printf("Adivinhe o numero entre 1 e 16.\n");

        while (tentativas < 4) {
            printf("Tentativa %i: ", tentativas + 1);
            printf("\nQual numero voce acha que e? ");
            scanf("%i", &palpite);
            
            if(palpite < 1){
            	printf("Insira um numero valido. Lembre-se: o numero e entre 1 e 16.\n");
            	continue;
			}
			
			if(palpite > 16){
				printf("Insira um numero valido. Lembre-se: o numero e entre 1 e 16.\n");
				continue;
			}
            
            if (numaleatorio == palpite) {
                printf("Voce acertou. O numero era %i.\n", numaleatorio);
                break;
            } else if (numaleatorio > palpite) {
                printf("Voce errou. O numero e maior.\n");
            } else if (numaleatorio < palpite) {
                printf("Voce errou. O numero e menor.\n");
            }
            
            tentativas++;
        }

        if (tentativas == 4) {
            printf("Suas tentativas acabaram. O numero era %i.\n", numaleatorio);
        }
        
        printf("Quer jogar de novo? (Digite 'n' (minusculo) para finalizar e qualquer coisa pra continuar: (*E pressione enter*)): ");
        scanf(" %c", &resp);  

    } while (resp != 'n');

    printf("Jogo finalizado.\n");

    return 0;
}
