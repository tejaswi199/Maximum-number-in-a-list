#Approach-1
n=int(input())
a=list(map(int,input().split()))
print(a)
m=0
for i in range(n):
  if m<a[i]:
    m=a[i]
print(m)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
print(a)
print(max(a))

#Approach-3
n=int(input())
a=list(map(int,input().split()))
print(a)
m=0
for i in a:
  if i>m:
    m=i
print(m)
