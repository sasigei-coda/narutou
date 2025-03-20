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

def all_digits_odd(n):
    return all(int(digit) % 2 != 0 for digit in str(n))

numbers = [num for num in range(1000, 3001) if all_digits_odd(num)]
print("@".join(map(str, numbers)))

  def slice_with_step(mylist, start, step):
    return mylist[start::step]

print(slice_with_step([1, 2, 33, 4, 5, 6, 7, 8, 9], 1, 2  
