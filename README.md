#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main()
{
char x[200];
scanf("%[^\n]",&x);
fflush(stdin);

int i=0;
int contA=0;
int contE=0;
int contI=0;
int contO=0;
int contU=0;
while(x[i]!='\0')
{
    if(x[i]=='a' || x[i]=='A')
        contA = 1;
    else if(x[i]=='e'|| x[i]=='E')
        contE = 1;
     else if(x[i]=='i'|| x[i]=='I')
        contI = 1;
         else if(x[i]=='o'|| x[i]=='O')
        contO = 1 ;
         else if(x[i]=='u'|| x[i]=='U')
        contU = 1;
        i++;



}


printf("VOGAL A: %d\n",contA);
printf("VOGAL E: %d\n",contE);
printf("VOGAL I: %d\n",contI);
printf("VOGAL O: %d\n",contO);
printf("VOGAL U: %d\n",contU);










return 0;
}
