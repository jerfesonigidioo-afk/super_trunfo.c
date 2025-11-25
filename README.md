 #include <stdio.h>

 int main(){


    char estado[50], codigodacarta[50], nomedacidade[50];
    int populacao, numerodepontosturisticos, carta;
    float PIB, area;

    printf("Insira os dados da sua carta\n");
    printf("UM EXEMPLO DE MODELO:\nCarta 1:\nEstado: A\nCódigo: A01\nNome da Cidade: São Paulo\nPopulação: 12325000\nÁrea: 1521.11 km²\nPIB: 699.28 bilhões de reais\nNúmero de Pontos Turísticos: 50\n");

    printf("\nCarta 1 ou 2: ");
    scanf("%i", &carta);

    printf("Estado: ");
    scanf("%s", estado);

    printf("Codigo da carta: ");
    scanf("%s", codigodacarta);

    printf("Nome da cidade: ");
    scanf("%s", nomedacidade);

    printf("Populacao: ");
    scanf("%i", &populacao);

    printf("Area (em km2): ");
    scanf("%f", &area);

    printf("PIB: ");
    scanf("%f", &PIB);

    printf("Numero de pontos turisticos: ");
    scanf("%i", &numerodepontosturisticos);

    printf("\nSUA CARTA TEM OS SEGUINTES ATRIBUTOS!\n");
    printf("carta: %i \n", carta);
    printf("Estado: %s \n", estado);
    printf("codigo da carta: %s \n", codigodacarta);
    printf("nome da cidade: %s \n", nomedacidade);
    printf("populaçao: %i \n", populacao);
    printf("Area: %.3f (em km2) \n", area);
    printf("PIB: %.3f de reais \n", PIB);
    printf("Numero de pontos turisticos: %i \n", numerodepontosturisticos);


 }
