#include <stdio.h>

int main() {
    float r, h, sb, sp, v, Pi;
    printf("r =");
    scanf("%f", &r);
        printf("h =");
    scanf("%f", &h);
    Pi=3.141;
    sb=2*Pi*h;
    printf("sb = %.2f \n",sb);
    sp=sb+2*Pi*r*r;
    printf("sp = %.2f \n",sp);
    v=Pi*r*r*h;
    printf("v = %.2f \n",v);
    return 0;
}
