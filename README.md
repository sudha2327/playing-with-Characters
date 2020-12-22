# playing-with-Characters

#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{
    char ch,s[50];
    char sen[100];
    scanf("\n%c",&ch);
    scanf("\n%s",&s);
    scanf("\n");
    scanf("%[^\n]%*c",&sen);
    
    printf("%c\n",ch);
    printf("%s\n",s);
    printf("%s",sen);
	   
    return 0;
}
