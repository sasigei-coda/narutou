# narutou
n=10
result=[]
if n>=1:
    result.append(1)
if n>=2:
    result.append(1)
for _ in range(2,n):
    result.append(result[-1]+result[-2])
print(result)



n=int(input())
result=1
for i in range(1,n+1):
    result *=i
print(result)
    
