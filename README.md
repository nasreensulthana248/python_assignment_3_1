# python_assignment_3_1
def sum(size):                 # size= 5 
    lst=[]                     #sample list: [8,2,3,0,7]
    result=0
    for x in range(size):
        ele=int(input())
        lst.append(ele)
    for x in range(size):
        result+=lst[x]         #Expected output: 20
    print(result)        
sum(int(input()))              #My output: 20
