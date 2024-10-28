#include <stdio.h>
#include <stdlib.h>

int main(){int n;int A[n][n],C[n][n],j,i;

printf("enter n:");
scanf("%d",&n);
printf("\n");

for(i=0;i<n;i++){
    for(j=0;j<n;j++){
        scanf("%c\t",&A[i][j]);

    }
}
printf(" A:");

printf("\n");

for(i=0;i<n;i++) {

    for(j=0;j<n;j++){
        printf("%c\t",A[i][j]);

    }
            printf("\n");
}


for(i=1;i<n;i++){
    for(j=0;j<n-i;j++){
    C[i][j]=A[i][j];

    }
}




printf("C:");

printf("\n");

for(i=0;i<n;i++) {

    for(j=0;j<n;j++){
        printf("%c\t",C[i][j]);

    }
            printf("\n");
}



    return 0;
}
