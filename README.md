#include<stdio.h>
int main()
{
   
   int a[5][5],b[5][5],rows,columns,i,j,c[5][5];
   printf("enter rows,columns:");
   scanf("%d%d",&rows,&columns);
   printf("enter 1 array");
   for(i=0;i<rows;i++)
   {
       for(j=0;j<columns;j++)
       {
           scanf("%d",&a[i][j]);
       }
   }
    printf("enter 2 array");
   for(i=0;i<rows;i++)
   {
       for(j=0;j<columns;j++)
       {
           scanf("%d",&b[i][j]);
       }
   }
   for(i=0;i<rows;i++)
   {
       for(j=0;j<columns;j++)
       {
           c[i][j]=a[i][j]+b[i][j];
       }
   }
     for(i=0;i<rows;i++)
   {
       for(j=0;j<columns;j++)
       {
           printf("%d",c[i][j]);
       }
       printf("\n");
   }   
}


output//
 
enter rows,columns:2 2                                                                                                        
enter 1 array 1 2 3 4                                                                                                         
enter 2 array 1 2 2 2                                                                                                         
24                                                                                                                            
56                      
