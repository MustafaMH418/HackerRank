```c

#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{

      
    char ch ;   // to store the character
    scanf("%c\n",&ch);
    char s[100];    // to store the string
    scanf("%s\n",&s);
    char sen[100];  // to store the sentence
    scanf("%[^\n]%*c",&sen);
    
    printf("%c\n%s\n%s",ch,s,sen);
    
    return 0;
}


```
