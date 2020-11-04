//# Mario-2
//To print mirrored steps as in Super Mario world
 #include<stdio.h>
int main(void){
 int num;
    do{
        printf("No of rows:");
         scanf("%d",&num);
    }
    while(num<1||num>8);

    for (int i=0;i<num;i++){
     for(int k=num;k>i;k--){
       printf(" ");
     }
   printf("#");

 for(int j=0;j<i;j++){
  printf("#");
 }
  printf("  ");
  for(int l=0;l<i+1;l++){
   printf("#");

  }
 printf("\n");
}
}
