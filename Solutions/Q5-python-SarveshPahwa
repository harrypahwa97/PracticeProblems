a=int(input('enter the number'))
b=[]
for i in range(0,a+1):
	if i%2==0:
		b.append(0)
	if i%2 !=0:
		b.append(1)
b[2]=1
b[1]=0
for i in range(3,a+1,2):
	for j in range(i*2,a+1,i):
		b[j]=0	
for i in range(0,a+1):
	if b[i]==0:
		print(i," is not Prime")
	else:
		print(i," is Prime")
