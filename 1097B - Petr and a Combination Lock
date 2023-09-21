n=int(input())  
lst=[]
for i in range(n):
    lst.append(int(input()))
    
for i in range(0,1<<n):
    ans=0
    for j in range(0,n):
        if i&(1<<j):
            ans+=lst[j]
        else:
            ans-=lst[j]
    ans=abs(ans)
    if ans==0 or ans%360==0:
        print("YES")
        break
if ans!=0 and ans%360!=0:
    print("NO")
