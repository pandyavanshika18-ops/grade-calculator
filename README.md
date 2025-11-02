# grade-calculator
#takes input from user and then gives percentage grade and total
n = int(input("Enter number of subjects: "))
t = 0
for i in range(n):
    m = float(input(f"Enter marks for subject {i+1}: "))
    t += m
p = t / n
print("Total:", t)
print("Percentage:", p)

if p >= 90:
    print("Grade: A+")
elif p >= 75:
    print("Grade: A")
elif p >= 60:
    print("Grade: B")
elif p >= 50:
    print("Grade: C")
else:
    print("Grade: F")
