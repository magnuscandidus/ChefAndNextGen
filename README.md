# ChefAndNextGen
# cook your dish here
t=int(input())
for i in range(t):
    a,b,x,y=map(int,input().split())
    if a*b<=x*y:
        print("yes")
    else:
        print("no")
