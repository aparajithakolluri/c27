#include <stdio.h>
void update(int *p){
    *p=50;
}
int main()
{
    int a=100;
    printf("given value: %d\n", a);
    update(&a);
    printf("updated value: %d\n", a);
    return 0;
}
