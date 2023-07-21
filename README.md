# BlackJack
import random
def oikosiena(number):
    result=0
    for i in range (1,number+1):
        xarti=random.randint(1,10)
        result+=xarti
        print(result)
number = int(input("write a number: "))
oikosiena(number)            
