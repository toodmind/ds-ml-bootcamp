Student Project: Study Habits and Exam Results
Date: February 3, 2026

1. What is this project about?
This project is about how much students study and how much they use the internet. I want to see if the internet makes the exam scores go down.
How I got the data: I asked my friends and other students in my class. I wrote down their answers in a list. Some people wrote "Male" and some just wrote "m". Also, some scores are numbers like 80, but some are words like "Pass". I did not fix the mistakes yet because I want to show the real data I collected.

2. The Information in the Data (Features & Labels)
In this data, we have things we look at (Features) and the result (Label).
•	The Features (X):
o	Age: How old is the student.
o	Gender: If the student is a Boy or a Girl.
o	Study_hours: How many hours they read books every day.
o	Internet_hours: How many hours they play on the phone or use social media.
•	The Label (y):
o	Exam_score: The mark the student got in the test. This is what we want to know.

3. How the data looks
The data has 100 rows and 5 columns. Here is a small part of it:
Age	Gender	Study_hours	Internet_hours	Exam_score
19	Female	3	6	65
22	Male	5	4	78
19	femle	3	2	86
18	F	2	5	55
21	M	4	3	72
19	Female	1	6	48
22	Male	5	4	Pass
20	female	3	7	60

4. Problems in the data
Because I wrote this by hand and asked people, there is many mistakes:
1.	Wrong Spelling: Sometimes I wrote "femle" or "Mael" instead of "Female" or "Male".
2.	Different Writing: For gender, I used "M", "Male", and "male". It is not the same.
3.	Missing Marks: Some students did not tell me their exam score, so the box is empty.
4.	Numbers and Words: Some scores are 70, but others are "Good" or "fail". I need to change words to numbers later.

5. How to use this for Machine Learning?

Getty Images
We can use this data to teach a computer:
•	Predicting Scores: The computer can learn that if you study 6 hours, you might get 90.
•	Pass or Fail: We can tell the computer to group students. For example, people who use internet 10 hours might fail.
•	Cleaning Practice: This is a good data for students to learn how to fix mistakes in Excel or Python.

