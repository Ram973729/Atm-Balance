# Atm-Balance
balance=10000
n=int(input('Enter the amount:'))
if n>balance:
    print('Error! Insufficient Balance.')
    print('Please Try Again!!!')
else:
    print('Credited Amount:',n)
    print('Main Balance:',balance-n)
