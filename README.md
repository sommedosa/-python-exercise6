# python-exercise6

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

>>2.1  </br>
>>for num in range(10, 0, -1):  </br>  
>>>print(num)  </br>  </br>
    
    
>>2.2     </br>
>>num = 1   </br>
>>while num < 11:   </br>
>>> print(num)   </br>
>>> num += 1   </br>
>>> #num += 2  # only odd numbers   </br>  </br>

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


>2.7  </br>

>a = 19  </br>
>b = 7  </br>
>false = a > b  </br>
>
>if false:   </br>
>>print(a)  </br>

>else:  </br>
>>print(b)  </br>  </br>



3. Fill in the blank(1) to complete the following program such that it can prevent a division-by-zero  </br>

>num1 = float(input('1st number: '))  </br>
>num2 = float(input('2nd number: '))  </br>
>if ______(1)______ :  </br>
>>print(num1,'is divisible by', num2)  </br>  </br>
   
   
4. Fill in the blank(1) to complete the following program   </br>

>num1 = float(input('1st number: '))  </br>
>num2 = float(input('2nd number: '))  </br>
>guess = float(input('Guess the average: '))  </br>

>avg = (num1+num2)/2.0  </br>

>if guess < avg:  </br>
>>print('It is too low')  </br>
>
>_____(1)______  </br>
>>print('It is too high')  </br>
>
>else  </br>
>>print('It is correct')  </br>  </br>
   

5. What gets prited  </br>

>x = True  </br>
>y = False  </br>
>z = False  </br>

>if not x or y:  </br>
>>print('1')  </br>
>
>elif not x or not y and z:  </br>
>>print('2')  </br>
    
>elif not x or y or not y and x:  </br>
>>print('3')  </br>
    
>else :  </br>
>>print('4')  </br>
