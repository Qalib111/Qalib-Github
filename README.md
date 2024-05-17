#include <stdio.h>

int main() {
    double num1, num2, product;

    // İstifadəçidən iki ədəd daxil etməsini istə
    printf("Birinci ədədi daxil edin: ");
    scanf("%lf", &num1);

    printf("İkinci ədədi daxil edin: ");
    scanf("%lf", &num2);

    // Ədədlərin hasilini hesabla
    product = num1 * num2;

    // Nəticəni ekrana çıxar
    printf("%.2lf və %.2lf ədədlərinin hasili %.2lf-dir.\n", num1, num2, product);

    return 0;
}
