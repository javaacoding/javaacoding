#include<stdio.h>
int main()
{
    int m ,n,a,b,c,d;
    printf("enter no of rows of matrix 1 : - ");
    scanf("%d",&m);
    printf("enter no of column of matrix 1 :- ");
    scanf("%d",&n);
    int a1[m][n];
    printf("enter all elements of matrix 1\n");
    for(int i = 0;i<m;i++){
        for(int j =0;j<n;j++){ 
     scanf("%d",&a1[i][j]);
        }
    }
        printf("MATRIX 1\n");
        for(int i = 0;i<m;i++){
        for(int j =0;j<n;j++){ 
     printf("%d ",a1[i][j]);
    }
    printf(" ");
    printf("\n");
  }
   printf("enter no of rows of matrix 2 : - ");
    scanf("%d",&a);
    printf("enter no of column of matrix 2 :- ");
    scanf("%d",&b);
    int a2[a][b];
    printf("enter all elements of matrix 2\n");
    for(int i = 0;i<a;i++){
        for(int j =0;j<b;j++){ 
     scanf("%d",&a2[i][j]);
        }
    }
        printf("MATRIX 2\n");
        for(int i = 0;i<a;i++){
        for(int j =0;j<b;j++){ 
     printf("%d ",a2[i][j]);
    }
    printf(" ");
    printf("\n");
  }
   printf("enter no of rows of matrix 3  : - ");
    scanf("%d",&c);
    printf("enter no of column of matrix 3 :- ");
    scanf("%d",&d);
    int a3[c][d];
    printf("enter all elements of matrix 3\n");
    for(int i = 0;i<c;i++){
        for(int j =0;j<d;j++){ 
     scanf("%d",&a3[i][j]);
        }
    }
        printf("MATRIX 3\n");
        for(int i = 0;i<c;i++){
        for(int j =0;j<d;j++){ 
     printf("%d ",a3[i][j]);
    }
    printf(" ");
    printf("\n");
  }
  int sum[m][d];
  printf("THE SUM OF MATRICES :-\n");
 for(int i = 0;i<c;i++){
        for(int j =0;j<d;j++){
            sum[i][j] = a1[i][j]+a2[i][j]+a3[i][j];
 printf("%d ",sum[i][j]);
 }
 printf(" ");
 printf("\n");
 }
    return 0;
}
