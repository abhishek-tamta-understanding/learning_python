# learning_python
This is my first Git Repository.
<br>
Author - Dr. Abhishek Kumar Tamta
<br>
#PYTHON
# Learned how to use print function. Using this I learned to write pattern
print('           1')     
print('        2, 3')
print('     4, 5, 6')
print(' 7, 8, 9, 10')
# Using print function wrote a letter to my future self
print('         Lieber Abhishek,')
print('')
print('         ich hoffe, dass du eine bessere Person bist.')
print('')
print('         Du bist sehr neugierige und freundliche Person.')
print('         Sei Gesund, sei glücklich!')
print('')
print('         Die Zukunft hat viele verschiedene Dinge für dich')
print('')
print('         Glückwunsch!')
print('')
print('         Viele Grüße')
print('         Abhishek')
# Data types
# Variable - used for storing data values. Each variable has a name and holds a value.
# 1) Integer - is a whole number. It has no decimal point and contains the number 0, positive and negative counting numbers.
# 2) Float - is a decimal number. It cam be used to represent fractions or precise measurements.
# 3) String - is used for storing text. Strings are wrapped in double or single quotes, "" or ''.
# 4) Boolean - stores a value that can only be either True or False. Also, in Python, it is always capitalized.
username = 'Abhishek'
deutsch_nievue = 3
course_progress = 3.9
pet_alive = False

print(username)
print(deutsch_nievue)
print(course_progress)
print(pet_alive)

# the % modulo operator doesn't give the result of a division, rather gives the remainder.
# Exponents are written as a**a for a x a or a^2, a square root can be written as 0.5
mass = 88 
height = 1.68 
bmi = (mass)/(height**2)
print('The BMI is', bmi)

# Code written to get Hypotenuse in Pythagorean theorem.
a = int(input('Value a,   '))
b = int(input('Value b,   '))
c = ((a*a) + (b*b)**0.5)

print('The Hypotenuse', c)
# Code for currency conversion
a = int(input('What do you have left in pesos?, '))
b = int(input('What do you have left in soles?, '))
c = int(input('What do you have left in reais?, '))

pesos = a*0.055
soles = b*0.29
reais = c*0.19
print('')
print('The dollars we have from pesos', pesos)
print('The dollars we have from soles', soles)
print('The dollars we have from reais', reais)

# Types of errors:
# 1) SyntaxError: This occurs when invalid Python code is present.
# 2) NameError: This occurs when one is trying to use a variable without declaring it first.
# 3) TypeError: This occurs when the data type one is using doesn't suit what one is trying to do.
