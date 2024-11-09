//Nesse código mostra como funciona o comando Char. O seu objetivo é o usuário colocar seu nome é aparecer duas vezes no final.//

#include "stdio.h"
#include "string.h"

int main()

    {
    char n1 [20], n2[20];
        printf ("Digite um nome: ");
            fgets (n1, 20, stdin);
            strcpy (n2,n1);
        printf ("nome 1: %s\n",n1);

        return 0;
    }
