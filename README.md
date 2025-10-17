# 6
gogen
n = int(input())
a = dict()
 
for _ in range(n):
    input()
    s = input()
    a[s] = a.setdefault(s, 0) + 1
k = 0
for i in a:
    if a[i] > 1:
        k += 1
print(k)
