# Mario-and-Transformation
# cook your dish here
for i in range (int(input())):
    n=int(input())
    if(n%3==0):
        print("Normal")
    elif((n-1)%3==0):
        print("Huge")
    else:
        print("Small")
