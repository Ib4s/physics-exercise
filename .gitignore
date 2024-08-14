#include <stdio.h>
#include <math.h>

int main()
{
    float A, d, ddp, C, E0, E, U, u, Q; 
    
    printf("1 - Um capacitor de placas paralelas cujo dielétrico é o ar é carregado com uma diferença de potencial de 600 V. A área das placas é 40 cm2 e a distância entre as placas é 1,0 mm. Determine:\n");
    
    printf("Qual é a área em metros?\n");
    scanf("%f", &A);
    
    printf("Qual é a distância em metros?\n");
    scanf("%f", &d);
    
    printf("Qual é a diferença de pontêncial?\n");
    scanf("%f", &ddp);
    
    E0 = 8.85*pow(10, -12);
    C = (E0 * A) / d;
    Q = C*ddp;
    U = (C*pow(ddp, 2))/2; 
    E = ddp/d;
    u = (E0*pow(E, 2))/2;
    
    printf("A - A capacitância é: %.2e.\n", C);
    printf("B - O valor absoluto da carga em uma das placas é: %.3e.\n", Q);
    printf("C - A energia armazenada é: %.3e.\n", U);
    printf("D - O campo elétrico na região entre as placas é de: %.0e.\n", E);
    printf("E - A densidade de energia na região entre as placas é de: %.3f.\n", u);
    
}
