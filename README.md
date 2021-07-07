# c-primer-
//chapter6 




int sum(int lower,int upper);
int main ()
{    int a,b;

    printf("enter lower and upper integer limits: ");

   while ( scanf("%d%d",&a,&b)== 2&&a<b)
    {



        printf("the sum of the squares from %d to %d is %d\n",a*a,b*b,sum(a,b));
        printf("enter lower and upper integer limits: ");

    }

    return 0;
}

int sum (int lower,int upper)
{     int sum =0;
    for(int i = lower;i <=upper; i++)
     {sum += i*i;
      }

      return sum;
}
