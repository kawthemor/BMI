w = int(input('enter your weight (kg) '))
h = int(input('enter your height (cm) '))
print('your weight =',w)
print('your height =',h)
bmi = w/((h/100)**2)
print(f'your BMI = {bmi:.2f}')
msg = 'you are '
if bmi < 16 : msg += 'severe thinness'
elif bmi <= 17 : msg += 'moderate thinness'
elif bmi <= 18.5 : msg += 'mild thinness'
elif bmi <= 25 : msg += 'normal'
elif bmi <= 30 : msg +=' overweight'
else : msg += 'obese'
print(msg)
