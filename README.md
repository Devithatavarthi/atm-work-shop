# atm-work-shop
pin=int(input("enter your 4 digit pin number:"))
spin=1234
balance=3000
if pin==spin:
    print("access granted")
    withdraw=int (input("enter amount:"))
    if withdraw>balance :
        print("insuffient balance")
    else:
        print("amount withdraw:",withdraw)
        print("remaining balance:",balance-withdraw)
        print("thank you for banking with us" )
else:
    print("access denied")
