# -python-exercise6

 1. Write a Python program to construct the following pattern, using a nested for loop.

>>&
>>& &
>>& & &
>>& & & &
>>& & & & &
>>& & & &
>>& & &
>>& &
>>&

2. What is the print out of the following program

>2.1
>for num in range(10, 0, -1):
>>print(num)
    
    
>2.2   
>num = 1 
>while num < 11: 
>> >>print(num) 
    num += 1 
    #num += 2  # only odd numbers 

>2.3 
>for num in range(1, 8): 
   >>print("T" * num) 
   
>2.4 
>times = 1 
>while times < 8: 
  >>print("T" * times) 
  >>times += 1 
    
>2.5  
>last_num = 12 
>**# i loop for columns, j loop for row**

>for i in range(0, 7) : 
>>for j in range(0, last_num) :
>>>print(end=" ") 

>>last_num = last_num - 2 
>>for j in range(0, i + 1): 
>>>print("T ", end="") 

>>print() 
        
>2.6
>x = 2
>x = x * 2 ** 3 ** 2 * 2 +2 /2
>print(x)


>2.7

>a = 19
>b = 7
>false = a > b
>
>if false: 
>>print(a)

>else:
>>print(b)



3. Fill in the blank(1) to complete the following program such that it can prevent a division-by-zero

>num1 = float(input('1st number: '))
>num2 = float(input('2nd number: '))
>if ______(1)______ :
>>print(num1,'is divisible by', num2)
   
   
4. Fill in the blank(1) to complete the following program 

>num1 = float(input('1st number: '))
>num2 = float(input('2nd number: '))
>guess = float(input('Guess the average: '))

>avg = (num1+num2)/2.0

>if guess < avg:
>>print('It is too low')
>
>_____(1)______
>>print('It is too high')
>
>else
>>print('It is correct')
   

5. What gets prited

>x = True
>y = False
>z = False

>if not x or y:
>>print('1')
>
>elif not x or not y and z:
>>print('2')
    
>elif not x or y or not y and x:
>>print('3')
    
>else :
>>print('4')
