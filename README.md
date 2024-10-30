# include <stdio.h>
int main () {
     int  A [4] [4]  ={ {1, 5, 9, 13 } , {2, 6, 10, 14 } , {3, 7, 11, 15} , {4, 8, 12, 16} } ;
int T , i , j ;
    for(i=0 ;i<4; i++){
       for(j=0; j<4;j++){
           printf ("%d\t" , A[i][j]);
            }
      printf("\n");
} 
for(i=0 ; i<4 ; i++){
      for(j=0 ; j<4 ; j++){
            A[i][j]=A[j][i];
                T=A[j][i];
        }
   } 
return 0;
}
