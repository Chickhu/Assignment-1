# Assignment-1
This is my first assignment 

Questions 1 Write a program that asks the user to enter their marks and displays
their grade:
• 90-100: A
• 80-89: B
• 70-79:C
• 60-69: D
Below 60: F
solution 
marks = int(input("Enter the marks: "))

if 90 <= marks <= 100:
    print("A")
elif 80 <= marks < 90:
    print("B")
elif 70 <= marks < 80:
    print("C")
elif 60 <= marks < 70:
    print("D")
else:
    print("Fail")