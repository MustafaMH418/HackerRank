```c
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int i = 4;
    double d = 4.0;
    char s[] = "HackerRank ";

    
    
    int j;
    double x;
    char str[100];
    char temp[100];
    
    scanf("%d",&j);
    scanf("%lf",&x);
    scanf("%c",temp); // to catch any starting space or \n
    scanf("%[^\n]",str); // scan until a new line is entered
     
    printf("%d\n",i+j);
    printf("%.1f\n",d+x);
    printf("%s",s);
    for(int i=0;i<strlen(str);i++){
      printf("%c",str[i]);
    }


    return 0;
}
```
