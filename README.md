# Working-with-Labview
This is a small work of mine on LabView .
The Questions are:

#Numeric, Stuctures, Boolean and TImings Palette

1)

• Create a VI that do the following
• adds two numbers
• subtracts one number from another
• multiplies two numbers together
• divides one number by another,
• squares the 1 st number,
• square roots the 1 st number,
• averages both numbers
• maximum of both numbers
• minimum of both numbers

All must use same input terminals, and same output terminal. Have an enumeration
control, that chooses the operation to be performed.

2)

Use a for loop to generate 50 random numbers. Determine the most current maximum and
minimum number as the random numbers are being generated. This is sometimes referred
to as a “running” maximum and minimum. Display the running maximum and minimum
values as well as the current random number on the front panel. Provide sufficient time gap
for the user to view the results. Display iteration count.

3)

Create a VI that generates an array of a specified length of uniformly distributed random
numbers with a range of (0-0.2] and from [0.3-1), In other words, the standard range for the
random number generator but without any values between 0.2 and 0.3. Calculate the
mean, standard deviation and root mean square of the array. User should be able to set the
default length of the array.

4)

Create a time trial program to compare the average execution times of the “Formula Node”
and the native LabVIEW Math Function. Display which method is fastest. To test the timing,
using the following formulas:
Where X is the input and Y is the output. Run the time trial for each of the
cases. Which method has the fastest execution time?

a = (X ^ 2) / 4;
b = 2X + 1;
Y = sin (a+b);




#Arrays

1. Construct a VI that computes the final grades in a course using three input arrays
containing students’ scores on three different exams.The input consists of three 1D
arrays: Exam 1 Scores (weighted 30% of the final grade); Exam 2 Scores (weighted
30% of the final grade); and Final Exam Scores (weighted 40% of the final grade). The
VI should output a 1D array containing the final course grade for each student. [Time
: 0.5 hr]

2. Build a VI that reverses the order of an array containing n random numbers.For
example, array[0] becomes array[n-1], array[1] becomes array[n-2] &amp; so on. Don’t
use reverse array function. [Time : 1hr]
Clusters

3. Design a VI that produces an array of clusters containing the course average, letter
grade, and class rank for each students in a class, given three arrays with the marks
obtained in three exams as input. The course average is % of sum of marks obtained
in three exams. The letter grade is determined from the course average by the
criteria list in the following table.

Course Average Letter Grade
0 - 59% F
60 - 69% D
70 - 79% C
80 - 89% B
90 - 100% A

Rank the students so that the student with the highest course average has a rank of
1 and the student with the lowest grade in the class has a rank equal to the number
of the students in the class. Display the array of cluster on the front panel. [Time :
1hr]
Strings

4. Design a VI which has the front panel as indicated. It should accept an array as input
&amp; display the sting size as output. [Time : 0.5 hr]

5 .Design a VI which indicates whether the string is palindrome or not. Don’t use
reverse string function. [Time : 1 hr]
File IO

6 .Write a code that gives following details for any selected VI - Selected VI Name, Selected
VI Path, Folder location of selected VI, Drive in which VI is present (C:\, D:\, etc). Write these
details in an ini file - with Section = VI name and Keys - as all other details. [Time : 0.5 hr]

7 .Build a VI that continuously measures the temperature once per second.If the
temperature goes above or below limits specified with front panel controls, the VI
turns on a front panel LED. After each measurement, logs the date, time (including
seconds), temperature, average of the last three measurements, and a one-word
message describing whether the temperature is “Normal” or “Over” or “Below” the
pre-set limit. The VI should log data so that each item appears in one column of a
spread sheet. The file should look like below and can have both .csv and tab-
delimited logging. [Time : 1hr]
