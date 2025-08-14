solution number 2 :
```c
#include<stdio.h>
int main()
{
    int i,A;
    scanf("%d",&A);
    for(i=1;i<=A;i++)
    {
        if(A%i==0)
        {
            printf("%d",i);

        }
    }
    return 0;
}
```
solution number 3:
```c
#include<stdio.h>
int main()
{
    int num,i;
    scanf("%d",&num);
    int a[num];
    for(i=0;i<num;i++)
    {
       scanf("%d",&a[i]);
    }
    int p = a[0],f=0;
    for(i=1;i<num;i++)
    {
        if(a[i]<p)
        {
            f=1;
        }
        p=a[i];
        if(f==0)
            printf("Yes\n");
        else
            printf("No\n");
    }

    return 0;
}
```

solution number 4 :
```c
#include<stdio.h>
int main()
{
    int K,M;
    scanf("%d%d",&K,&M);

    printf("%d",M%K);
    return 0;
}
```

solution number 6 :
```c
#include<stdio.h>
int main()
{
    int n,i;
    scanf("%d",&n);
    for(i=1;i<n;i++)
        n=n/i ;
        {
            printf("%d",n);
        }
        return 0;
}
```
