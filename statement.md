#include <stdio.h>
int main(void)
{
    int i = 0;
    char *t = "hello world";
    while(t[i] != '\0')
    {
        i++;
    }
    write(1,t,i);
    return(0);
}
