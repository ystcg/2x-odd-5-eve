def list_fun2(L):
    for i in range(len(L)):
        if L[i]%2==0:
            L[i]=L[i]//2
        else:
            L[i]=L[i]*2
List=eval(input("Enter the list elements:"))
print("The original list is:", List)
list_fun2(List)
print("The modified list is:", List)
