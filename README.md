# Determinant-of-Matrix-
#include<stdio.h>
#include<stdlib.h>
int main(){
    int d1,d2,d3,k;
    int a1,b1,c1;
    printf("ENTER THE VALUES OF A1 B1 C1 \n");
    scanf("%d%d%d",&a1,&b1,&c1);
    int a2,b2,c2;
    printf("ENTER THE VALUES OF A2 B2 C2 \n");
    scanf("%d%d%d",&a2,&b2,&c2);
    int a3,b3,c3;
    printf("ENTER THE VALUES OF A3 B3 C3 \n");
    scanf("%d%d%d ",&a3,&b3,&c3);
    d1 = a1*((b2*c3)-(c2*b3)); 
    d2 = a2*((b1*c3)-(c1*b3));
    d3 = a3*((b1*c2)-(c1*b2 ));
    k =  d1-d2+d3;
   printf("THE DETERMINANT OF THE 3*3 MATRIX IS : %d",k);
   return 0;
}