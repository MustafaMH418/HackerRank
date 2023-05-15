```c
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
  
    int cnt,sum;
    scanf("%d", &cnt);
    int *arr = malloc(cnt * sizeof(int));
     sum = 0;
    while (cnt--)
    {
        scanf("%d", arr);
        sum += *arr++;
    }
    printf("%d", sum);
    return 0;
   
}

```
