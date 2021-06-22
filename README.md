#Welcome To Prog Theta
int t, n, c1=0, c2=0;
   scanf("%d",&t);

   for(int i=1; i<=t; i++)
   {
       scanf("%d",&n);
       if(n>10){
           printf("%d %d\n",10, n-10);
       }
       else{
           printf("%d %d\n",0,n);
       }
   }
