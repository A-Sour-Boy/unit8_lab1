# Lab Reflection: Git Version Control + Debugging (BuggyProgram)

## Student Name
Travis Doughty

## GitHub Repository URL
https://github.com/A-Sour-Boy/unit8_lab1
---

# Commit 1: Initial Commit

## What did you include in this commit?
- The starter files for the project, including BuggyProgram.java and README.md.

## What was the purpose of this commit?
- To create a starting point before making any changes.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- The tests that checked the grade categories were failing.

## What was the issue in the code?
- The grade labels for scores above 90 and above 80 were reversed.

## What change did you make to fix it?
- I changed scores above 90 to return "Exceeds" and scores above 80 to return "Meets".

## How did the tests help guide your fix?
- The tests showed that the method was returning the wrong grade category.

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- The tests involving arrays with even numbers were failing.

## What was the issue in the code?
- The sum started at 1 instead of 0, and the loop went past the end of the array.

## What change did you make to fix it?
- I changed the starting sum to 0 and changed the loop condition to use `< values.length`.

## How did the tests help guide your fix?
- The tests showed incorrect totals and helped identify the loop error.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- The tests related to summing a range of numbers.

## What was the issue in the code?
- I reviewed the loop boundaries and verified the method's logic.

## What change did you make to fix it?
- I ensured the method correctly sums all numbers from the start value to the end value.

## How did the tests help guide your fix?
- The tests confirmed that the method produced the expected totals.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
- Task 1 was the easiest because it only required correcting conditional statements.

## Which task was the most difficult? Why?
- Task 2 was the most difficult because it involved multiple bugs in the loop logic.

## How did Git help you track your progress through the debugging process?
- Git allowed me to save changes and keep a history of my work.

## Why is it important to make small, frequent commits when debugging code?
- Small commits make it easier to identify and undo mistakes.

## What did you learn about using JUnit tests to guide debugging?
- JUnit tests help identify problems quickly and verify that fixes work.

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
- I fixed the bugs, reviewed the code, and completed the README reflection.

## Why is it useful to document your work after completing a programming task?
- Documentation helps explain changes and makes the project easier to understand later.

README reviewed and updated.
