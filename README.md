# currency-converter
def main():

Print_menu()
currency_converter()
def Print_menu():

print('Please choose from the menu.')       
print('============================')       
print('1: Convert between USD and EUR')     
print('2: Convert between USD and Canada')  
print('3: Convert between USD and UK (GBP)')
print('4: Convert between USD and China')   
print('5: Quit')                            
print('============================')       
menu = int(input('Enter your Choice: '))
def currency_converter():

while menu >=1 and menu <=4:
    if menu == 1:
         menu = int(input('Enter the amount in dollar: '))
         men1 = menu 
         men1 = menu * 91/100 
         print('\t','$', menu,'is', format(men1,'.2f'),'euro')
    elif menu == 2:
        menu = int(input('Enter the amount in dollar: '))
        men1 = menu 
        men1 = menu * 137/100 
        print('\t','$', menu, 'is', format(men1,'.2f'), 'cad')
    elif menu == 3:
        menu = int(input('Enter the amount in dollar: '))
        men1 = menu 
        men1 = menu * 72/100 
        print('\t','$', menu, 'is', format(men1,'.2f'), 'pound')
    elif menu == 4:
        menu = int(input('Enter the amount in dollar: '))
        men1 = menu 
        men1 = menu * 653/100 
        print('\t','$', menu, 'is', men1, 'yuan')

if menu == 5:
    print('Thank you for using my program.')

else:
    print(menu, 'is an invalid choice.')
