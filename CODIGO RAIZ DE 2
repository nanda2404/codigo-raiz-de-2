// CÓDIGO PARA O CALCULO DA RAIZ QUADRADA DE 2 PELO METODO DE NEWTON
#include <stdio.h>
#include <math.h>
int main() {
    double x = 1.0;       
    const int MAX_IT = 20;
    const double EPS = 1e-6;
    printf("Iteração\tAproximação\n");
    for (int i = 0; i < MAX_IT; i++) {
        x = (x + 2.0 / x) / 2.0;   
        printf("%d\t\t%.10f\n", i + 1, x);  
        if (fabs(x * x - 2) < EPS) 
            break;
    }
    return 0;
}
