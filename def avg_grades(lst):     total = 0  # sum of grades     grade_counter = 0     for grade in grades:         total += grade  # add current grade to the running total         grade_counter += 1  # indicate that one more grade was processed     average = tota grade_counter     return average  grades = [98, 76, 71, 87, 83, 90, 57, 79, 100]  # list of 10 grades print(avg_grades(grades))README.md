- 👋 Hi, I’m @EKHALID11
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
EKHALID11/EKHALID11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->def avg_grades(lst):
    total = 0  # sum of grades
    grade_counter = 0
    for grade in grades:
        total += grade  # add current grade to the running total
        grade_counter += 1  # indicate that one more grade was processed
    average = total / grade_counter
    return average

grades = [98, 76, 71, 87, 83, 90, 57, 79, 100]  # list of 10 grades
print(avg_grades(grades))
