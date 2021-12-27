x=[20,21,65,85,98,78,45,95,78,95,73,66,44,55,88,77,48,22,33,12]
print(x)
avg=sum(x)/len(x)
print(avg)
print(max(x))
print(min(x))
x.sort()
print(x)
print('second largest number',x[-2])
print('second smallest number',x[1])
for num in x:
  if num%2==0:
    count=count+1
print(count)
