# prime-python
n=int(input("enter your number"))
i=0
j=1
for i in range(0,n):
    
    logic = 0
    for j in range(1,n):
        if i%j==0:
            logic+=1
    if logic==2:
        print(i) 
