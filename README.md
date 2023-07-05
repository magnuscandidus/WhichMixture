# WhichMixture
# cook your dish here
t=int(input())
while t:
    a,b=map(int,input().split())
    if(a>0 and b>0):
        print("Solution")
    elif(b==0):
        print("Solid")
    else:
        print("Liquid")
    t-=1
