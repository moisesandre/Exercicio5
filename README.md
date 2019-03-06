# Exercicio5

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i,cont=0;

    for (i=1; i<=100; i++)
    {
        printf("numeros: %d\n",i);
        cont=cont+i;
    }

    printf("Soma dos numeros: %d",cont);

    return 0;
}
