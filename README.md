1. A imobiliária Imóbilis vende apenas terrenos retangulares. Faça um algoritmo para ler as dimensões de um terreno e depois exibir a área do terreno.

   #include<stio.h>
 #include<stdlib.h>
 
 int main()
 {
     float L,C,A;
     printf("Digite a largura do lote:");
     scanf("%f",&L);
     printf("Digite o cumprimento do lote:'
     scanf("%f",&C);
     A = L*C;
     printf("A area do lote = %.2f", A);
     return 0;
     
     }
