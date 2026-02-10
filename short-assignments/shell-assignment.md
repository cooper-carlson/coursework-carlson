# Shell Assignment
author: Cooper Carlson
date: 2026-02-03

# Task 1
mkdir short-assignments

# Task 2
cd short-assignments/
cd north-pacific-gyre/
ls

# Task 3
mkdir NENE-A
mkdir NENE-B
mv NENE01729A.txt NENE01736A.txt NENE01751A.txt NENE01812A.txt NENE01843A.txt NENE01978A.txt NENE02040A.txt NENE02043A.txt NENE-A
mv NENE01729B.txt NENE01751B.txt NENE01843B.txt NENE01978B.txt NENE02018B.txt NENE02040B.txt NENE02043B.txt NENE-B

# Task 4
wc -l NENE-A/*.txt
wc -l NENE-B/*.txt
The file with the fewest lines is NENE-B/NENE02018B.txt

# Task 5
rm *Z.txt

# Task 6
within Vim:
:wq
back in the terminal window:
cd ..
cd ..
mv shell-assignment.md short-assignments/

