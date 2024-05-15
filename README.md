# AtividadeComC3

#include <stdio.h>
#include <stdlib.h>

int main() { 

float base;
float altura;


// Cálculo de media de 4 notas
    printf("Digite a base do retangulo: ");
	scanf("%f", &base);
	printf("Digite a altura: ");
	scanf("%f", &altura);

	float area = base * altura;
	printf("A area do retangulo e:%f", area);
	
return 0;
}
