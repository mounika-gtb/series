# series
x,n=map(int,input().split())
sum=0
for i in range(0,n+1):
   if i<=n:
      sum=sum+pow(x,i)
print(sum)
   
 
