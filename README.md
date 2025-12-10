# STUDENYT-DETAIL-AND-MARKS

name = input("Enter Student Name: ")
roll = input("Enter Roll Number: ")
course = input("Enter Course Name: ")
# Taking marks of 5 subjects
print("\nEnter marks out of 100:\n")
s1 = int(input("Subject 1: "))
s2 = int(input("Subject 2: "))
s3 = int(input("Subject 3: "))
s4 = int(input("Subject 4: "))
s5 = int(input("Subject 5: "))

# Calculating total and percentage
total = s1 + s2 + s3 + s4 + s5
percentage = total / 5
# Calculating grade using conditional statements
if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B+"
elif percentage >= 60:
    grade = "B"
elif percentage >= 50:
    grade = "C"
else:
    grade = "Fail"
# Printing the marksheet
print("\n============== STUDENT MARKSHEET ==============")
print("Name        :", name)
print("Roll Number :", roll)
print("Course      :", course)
print("-----------------------------------------------")
print("Subject 1   :", s1)
print("Subject 2   :", s2)
print("Subject 3   :", s3)
print("Subject 4   :", s4)
print("Subject 5   :", s5)
print("-----------------------------------------------")
print("Total Marks :", total)
print("Percentage  :", percentage, "%")
print("Grade       :", grade)
print("===============================================")
