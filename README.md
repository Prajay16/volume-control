# volume-control
#include <stdio.h>

int main(void) {
    int T,i,X,Y,N;
    scanf("%d",&T);
    for(int i=0;i<T;i++){
        scanf("%d%d",&X,&Y);
        if(Y>X){
      int N=Y-X;
       printf("%d\n",N);
        }
        else{
            int N=X-Y;
            printf("%d\n",N);
        }
    }
	return 0;
}
