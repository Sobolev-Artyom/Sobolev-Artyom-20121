# Listing 4_1
____
### На вход поступает целое число, вернуть true, если число является целым палиндромом. Целое число является палиндромом, если оно читается так же, как в прямом, так и в обратном порядке.
```Py
def main():
    pm = (input())          // input number
    if (pm) == (pm)[::-1]:      // check,if  the number has reverse version 
        print("True")      // it is if yes
    else:
        print("False")    //it is if no
        
if __name__=="__main__":
    main()
```
## How it works
```
### Input: 121
Output: True
Input: 123
Output: False
```
____
#Listing 4_2
____
###

