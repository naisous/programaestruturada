#1. A imobiliária Imóbilis vende apenas terrenos retangulares. Faça um algoritmo para ler as dimensões de um terreno e depois exibir a área do terreno.
  
  #include<stdio.h>
#include<stdlib.h>

int main()
{
    float L, C, A;
    printf("Digite a largura do lote:");
    scanf("%f", &L);
    printf("Digite o cumprimento do lote:");
    scanf("%f", &C);
    A = L*C;
    printf("A area do lote = %.2f", A);
    return 0;

}

   2. Faça um programa que calcule e mostre a área de um trapézio. Sabe-se que: A = (base maior + base menor) * altura)/2

#include<stdio.h>
#include<stdlib.h>
int main()
{
    float A, BM, BMN, AL;
    printf("###########################");
    printf("\nCalcule a base de um trapezio\n");
    printf("###########################");
    printf("\nDigite a base maior: ");
    scanf("%f",&BM);
    printf("Digite a base menor: ");
    scanf("%f",&BMN);
    printf("Digite a altura: ");
    scanf("%f",&AL);

    A = ((BM+BMN)*AL)/2;
    printf("O valor da area do trapezio é: %f", A);
    return 0;
}
   3. Faça um algoritmo para calcular quantas ferraduras são necessárias para equipar todos os cavalos comprados para um haras.
   
   #include<stdio.h>
#include<stdlib.h>

int main()
{
    int cava, ferra, patas;
    patas = 4;
    printf("Digite o numero de cavalos adquiridos:");
    scanf("%i", &cava);
    ferra = cava*patas;
    printf("É necessario %i ferraduras.", ferra);
    return 0;
}

   4. O restaurante a quilo Bem-Bão cobra R$12,00 por cada quilo de refeição. Escreva um algoritmo que leia o peso do prato montado pelo cliente (em quilos) e imprima o valor a pagar. Assuma que a balança já desconte o peso do prato.

#include<stdio.h>
#include<stdlib.h>
int main()
{
    int pesoprato;
    float total, peso, quilo;
    quilo = 12.00;
    pesoprato = 2;
    printf("Digite o peso do prato pronto em (Quilos e gramas) :");
    scanf("%f",&peso);
    total = (quilo*peso)-pesoprato;
    printf("O valor de sua refeição é R$%.2f.", total);
    return 0;
}
   
   5. A padaria Hotpão vende certa quantidade de pães franceses e uma quantidade de broas a cada dia. Cada pãozinho custa R$ 0,12 e a broa custa R$ 1,50. Ao final do dia, o dono quer saber quanto arrecadou com a venda dos pães e broas (juntos), e quanto deve guardar numa conta de poupança (10% do total arrecadado). Você foi contratado para fazer os cálculos para o dono. Com base nestes fatos, faça um algoritmo para ler as quantidades de pães e de broas, e depois calcular os dados solicitados.


#include<stdio.h>
#include<stdlib.h>

int main()
{
int paes, broas;
float porce, total;
printf("Digite a quantidade de paes que forao vendidos:");
scanf("%i", &paes);

printf("Digite a quantidade de broas que forao vendidos:");
scanf("%i", &broas);

printf("Total de paes e broas vendidas: %i", paes+broas);
total= paes*0.12 + broas*1.50;
printf("\nValor Arrecadado %.2f$",total);
porce = total*10/100;
printf("\nTotal a ser colocado na pupança  é : %.2f Porcento", porce
