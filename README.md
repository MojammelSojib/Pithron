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

1 to N SUM

#include <stdio.h>
int main()
{
    long long int x,sum=0;
    scanf("%lld",&x);

    for(int i=1;i<=x;i++)
    {
        sum+=i;
    }
    printf("%lld",sum);
    return 0;
}

Even Number
#include<stdio.h>
int main()
{
    int n,m;
    scanf("%d",&n);

    m=(n-20)/5;
    printf("%d %d %d %d %d",m,m+2,m+4,m+6,m+8);
    return 0;

}

ODD Number

#include<stdio.h>
int main()
{
    int n,m;
    scanf("%d",&n);

    m=(n-16)/4;
    printf("%d %d %d %d",m+1,m+3,m+5,m+7);
    return 0;

}
