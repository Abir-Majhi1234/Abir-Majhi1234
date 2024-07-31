#include<stdio.h>

int main()
{
    int row,column;
    
    printf("Enter the row :\n");
    scanf("%d",&row);
    printf("Enter the column :\n");
    scanf("%d",&column);
    
    int a[row][column];
    //printf("a[%d][%d]",row,column);
    for(int i=0;i<row;i++)
    {
        for(int j=0;j<column;j++)
        {
            printf("Enter the a[%d][%d] value\n",i,j);
            scanf("%d",&a[i][j]);
        }
    }
    
    return 0;
    
}
