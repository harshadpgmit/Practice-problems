# Practice problem no 1: show the scored results are pass, fail or fcd
#When i am learning
total_marks = 500
marks_scored = 350
passing_per = 35
per = (marks_scored / total_marks)*100
print(per)
if per>=70:
    print("fcd")
elif per>=35:
    print("pass")
else:
    print("Fail")
## output fcd
    
    
 # practice problem no 2 : enter a number and show either it is even or odd
num = 45
if num % 2 == 0:
  print("even")
else:
  print("odd")
## output odd


 # practice problem no 3: enter a alphabet and show either it is an vowel or consonant
 l =['a','e','i','o','u']
value = 'a'
if value in l:
    print("vowel")
else:
    print("consonant")
 ## output vowel
 
 
