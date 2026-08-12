[pythan.py](https://github.com/user-attachments/files/30962957/pythan.py)
print("---------------welcome to the career guiding app-----------------  ")
print("enter your details to get started")
a = input("WHAT IS YOUR NAME: ")
b = input("WHAT IS YOUR AGE: ")
print("hello", a, "we will help you to choose your career path")
print("please answer the following questions to help us guide you better")
print( """1. What is your favorite subject generally?
a) English
b) Maths
c) Science
Your choice: """)
sb = "English"
sb2 = "Maths"
sb3 = "Science"
d = input().strip().lower()
if d == sb.lower():
    print("hmm... " + sb + " subject is a very smart choice!")
    print("Here are some career options for you based on your choice of subject:")
    print("1. If you chose English, you can consider careers in writing, journalism, teaching, or public relations.")
elif d == sb2.lower():
    print("hmm... " + sb2 + " subject is a very smart choice!")
    print("Here are some career options for you based on your choice of subject:")
    print("2. If you chose Maths, you can consider careers in finance, data analysis, engineering, or actuarial science.")
elif d == sb3.lower():
    print("hmm... " + sb3 + " subject is a very smart choice!")
    print("Here are some career options for you based on your choice of subject:")
    print("3. If you chose Science, you can consider careers in research, medicine, environmental science, or pharmaceuticals.")
else:
    print("Sorry, that is not a valid choice. Please enter english, maths, or science.")
print("Thank you for using the career guiding app! We hope this helps you in making an informed decision about your future career path.")



