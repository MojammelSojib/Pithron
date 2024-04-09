# Pithron

 Eid Vacation Practice Set 
 Salary
 
 #include <stdio.h>

int main() {

     int x;
    scanf("%d",&x);
    printf("%lld",(long long int)x*365);
   
    return 0;
}

Divisor & Dividend

#include <stdio.h>
int main() 
{
    
    int d,q,r;
    scanf("%d %d %d",&d,&q,&r);
    int divisor;
    
    divisor=(d-r)/q;
    
    printf("%d",divisor);
    
    return 0;
}

Father and Daughter
#include <stdio.h>
int main()
{
    int x,d,f;
    scanf("%d",&x);

    d=x/5;
    f=d*4;
    printf("%d %d",f,d);
    return 0;

}
