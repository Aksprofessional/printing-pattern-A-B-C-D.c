# printing-pattern-A-B-C-D.c
//C program to print pattern   A BC DEF GHIJ KLMNO 
//C program to print pattern 

A
BC
DEF
GHIJ
KLMNO

#include <stdio.h>
int main() {
    int i,j,a=0;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=i;j++){
         printf("%c",65+a);
         a++;
        }
        printf("\n");
    }
    return 0;
}
