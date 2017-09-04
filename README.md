# Poker
#include <stdio.h>
#define MAX 1000
int main(int argc, char const *argv[])
{
    int n, play1[MAX], play2[MAX], i, cartas, o, k, teste=0;;

    /*Quantidade de partidas*/
    printf("Quantidade de partidas: ");
    scanf("%d",&n);


    for(i=0;i<n;i++)
    {

        for(o=0;o<5;o++)
        {

            scanf("%d",&play1[o]);
        }
        for(k=0;k<5;k++)
        {

            scanf("%d",&play2[k]);
        }
    }
    
    teste++;
    printf("Teste %d",teste);

    return 0;
}
