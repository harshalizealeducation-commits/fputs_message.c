
#include <stdio.h>

int main()
{
    FILE *fp;

    fp = fopen("message.txt", "w");

    if (fp == NULL)
        return 1;

    fputs("C Programming is Easy!", fp);

    fclose(fp);

    return 0;
}
