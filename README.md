// array declare and initialiging

#include <stdio.h>
int main() {
int i, array[5];
array[0]=1;
array[1]=2;
array[2]=3;
array[3]=4;
array[4]=5;
array[5]=6;
for(i=0; i<5; i++)
{
    printf("array[%d]=%d\n", i,array[i]);
}
    return 0;
}
