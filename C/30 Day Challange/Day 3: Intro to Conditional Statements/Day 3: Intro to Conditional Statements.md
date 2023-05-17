```c
int main()
{
    int N = parse_int(ltrim(rtrim(readline())));
    
    if(N%2 == 1) printf("Weird");
    else if(N>=2 && N<=5) printf("Not Weird");
    else if(N>=6 && N<=20) printf("Weird");
    else if(N%2==0 && N>20) printf("Not Weird");
    
    return 0;
}
```
