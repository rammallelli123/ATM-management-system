# ATM-management-system
# this is the one who helps the people andeasy   to withdraw  or deposite our money to our bank through ATM
#it is used to deposite
#it is also used towithdraw
#it is also used to check our bank balance
#it is used to  easy transaction
#it is used to easy money taking process
4![2021-12-19](https://user-images.githubusercontent.com/96358791/146659363-c1b725fc-3150-4c8d-a6c7-23127846528b.png)
username='mohan'
password='***'

c_name=input("enter your name:")
c_pass=str(input("enter your password:")) 

if c_name==username and c_pass==password:
    print('''
    1.Deposite
    2.withdraw
    3.mini_statement
    4  .exit
    ''')
    amount=10000
    option=int(input("select your option:"))
    if option==1:
        dep=int(input("enter thr amount"))
        amount+=dep
        print("total amount:",amount)
    elif option==2:
        withd=int(input("enter th amount:"))
        amount-=withd
        print("total amount:",amount)
    elif option==3:
        print("=======ATM=======")
        print("username:",username)
        print("total amount:",amount)
        print("thanks for visiting")
        print("==================")
    elif option==4:
        exit()
else:
    print("please enter correct logins")
