# -python-exercise6

 1. Write a Python program to construct the following pattern, using a nested for loop.  </br>  </br>

>>&  </br>
>>& &  </br>
>>& & &  </br>
>>& & & &  </br>
>>& & & & &  </br>
>>& & & &  </br>
>>& & &  </br>
>>& &  </br>
>>&  </br>

2. What is the print out of the following program  </br>  </br>

>2.1  </br>
>for num in range(10, 0, -1):  </br>  
>>print(num)  </br>  </br>
    
    
>2.2     </br>
>num = 1   </br>
>while num < 11:   </br>
>> print(num)   </br>
>> num += 1   </br>
>> #num += 2  # only odd numbers   </br>  </br>

>2.3   </br>
>for num in range(1, 8):   </br>
   >>print("T" * num)   </br>  </br>
   
>2.4   </br>
>times = 1   </br>
>while times < 8:   </br>
  >>print("T" * times)   </br>
  >>times += 1   </br>  </br>
    
>2.5    </br>
>last_num = 12   </br>
>**# i loop for columns, j loop for row**  </br>

>for i in range(0, 7) :   </br>
>>for j in range(0, last_num) :  </br>
>>>print(end=" ")   </br>

>>last_num = last_num - 2   </br>
>>for j in range(0, i + 1):   </br>
>>>print("T ", end="")   </br>

>>print()   </br>  </br>
        
>2.6  </br>
>x = 2  </br>
>x = x * 2 ** 3 ** 2 * 2 +2 /2  </br>
>print(x)  </br>  </br>


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
