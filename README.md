# 2D-Array


#include <stdio.h>

void BOX()
{
    //Declaring Variable
     int box[2][3];

  for(int i=0;i<2;i++)
 {
     for(int j=0;j<3;j++)
     {  
         //Taking Inputs
         printf("Please Give Input Here :\n");
         scanf("%d ",&box[i][j]);
     }
 } 
 
 
 
 printf("Giving Outputs :\n");
 
 
 for(int i=0;i<2;i++)
 {
     
     for(int j=0;j<3;j++)
     {
         
     printf("a[%d][%d] = %d \n",i+1,j+1,box[i][j]);
     
     }
     
 }
 
 
 
}



int main() 
{
 //Calling Function
 BOX();
  
    return 0;
}
