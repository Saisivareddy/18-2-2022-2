# 18-2-2022-2
n=int(input("enter ur number"))

c=0

for i in range(1,n+1):

    temp=0

    for j in range(2,i,1):

        if(i%j==0):

            temp=1

            break;

    if(temp==0):

        c=c+1

print("total prime no's=",c)
