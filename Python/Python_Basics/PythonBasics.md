

```python
print('Hello World')
```

    Hello World
    


```python
name = input('What is your name?')

print('Hello '+ name +' it is very nice to meet you!')
```

    What is your name?Matthew
    Hello Matthew it is very nice to meet you!
    


```python
age = input('how old are you? ')

next_year = int(age) + 1

print('Next year you will be '+ str(next_year) + ' years old!')
```

    how old are you? 27
    Next year you will be 28 years old!
    


```python
question_1 = input(' how many months have you been coding? ')

if int(question_1) > 5:
    print('Wow you would make a great junior level employee!')
else:
    print('You should study more!')
```

     how many months have you been coding? 8
    Wow you would make a great junior level employee!
    


```python
answer = 'yes'
while answer == 'yes':
    print('You can only win with coding!')
    answer = input('Is coding the best way to get ahead in life?')
    
```

    You can only win with coding!
    Is coding the best way to get ahead in life?yes
    You can only win with coding!
    Is coding the best way to get ahead in life?yes
    You can only win with coding!
    Is coding the best way to get ahead in life?absolutely
    
