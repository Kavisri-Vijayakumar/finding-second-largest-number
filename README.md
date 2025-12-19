# finding-second-largest-number
a=[]
n=int(input("enter number of elements: "))
for i in range(1,n+1):
  b=int(input("enter element: "))
  a.append(b)
a.sort()
print("second largest element is: ",a[n-2])


enter number of elements: 5
enter element: 1
enter element: 23
enter element: 456
enter element: 7890
enter element: 14785
second largest element is:  7890
