#include <stdio.h>

int main() {

    int idade;

    printf("Digite a idade do nadador: ");
    scanf("%d", &idade);

    if(idade <= 12) {
        printf("Categoria: Infantil\n");
    }
    else if(idade >= 13 && idade <= 17) {
        printf("Categoria: Juvenil\n");
    }
    else {
        printf("Categoria: Adulto\n");
    }

    return 0;
}
