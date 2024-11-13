students_count = int(input())
failed = good = very_good = top = 0
total_grades = 0

for _ in range(students_count):
    grade = float(input())
    total_grades += grade
    if 2.00 <= grade <= 2.99:
        failed += 1
    elif 3.00 <= grade <= 3.99:
        good += 1
    elif 4.00 <= grade <= 4.99:
        very_good += 1
    elif 5.00 <= grade <= 6.00:
        top += 1

failed_percent = failed / students_count * 100
good_percent = good / students_count * 100
very_good_percent = very_good / students_count * 100
top_percent = top / students_count * 100
average_grade = total_grades / students_count

print(f"Top students: {top_percent:.2f}%")
print(f"Between 4.00 and 4.99: {very_good_percent:.2f}%")
print(f"Between 3.00 and 3.99: {good_percent:.2f}%")
print(f"Fail: {failed_percent:.2f}%")
print(f"Average: {average_grade:.2f}")
