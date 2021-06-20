# Take-input-from-user-and-check-it-is-triangle-or-not-using-python
ang1=input('Enter angle of one side: ')
ang2=input('Enter angle of two side: ')
ang3=input('Enter angle of third side: ')
sum=int(ang1)+int(ang2)+int(ang3)
if sum==180:
    print('This is Triangle.......')
else:
    print('This is not Triangle.....')
