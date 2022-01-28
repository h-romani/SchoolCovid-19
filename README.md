# Student Covid Cases in Ontario School Boards

A python command-line program that explores covid cases (Government of Ontario record csv files) among Ontario school board students under 18. The user can find specifically which schools are more likely to be affected by coronaviruses and which schools are taking the precautionary measures to ensure their students' safety. 


To run the program through the command-line (Exploring the region of Missisauga school districts)

```
python school_covid19.py SORTED_CSV_FILES/studentCOVID.csv Mississauga
```

```
Data, School Board, Total Confirmed Case(s)
2020-09-11, York Region District School Board, 1
2020-09-14, Peel District School Board, 2
2020-09-15, Dufferin Peel Catholic District School Board, 4
2020-09-16, Dufferin Peel Catholic District School Board, 5
2020-09-17, Dufferin Peel Catholic District School Board, 7
2020-09-18, Dufferin Peel Catholic District School Board, 7
2020-09-21, Dufferin Peel Catholic District School Board, 9
2020-09-22, Dufferin Peel Catholic District School Board, 10
2020-09-23, Dufferin Peel Catholic District School Board, 14
2020-09-24, Dufferin Peel Catholic District School Board, 16
2020-09-25, Dufferin Peel Catholic District School Board, 17
2020-09-28, Dufferin Peel Catholic District School Board, 18
2020-09-29, Dufferin Peel Catholic District School Board, 16
2020-09-30, Dufferin Peel Catholic District School Board, 18
2020-10-01, Dufferin Peel Catholic District School Board, 18
2020-10-02, Dufferin Peel Catholic District School Board, 19
2020-10-05, Dufferin Peel Catholic District School Board, 20
2020-10-06, Dufferin Peel Catholic District School Board, 21
2020-10-07, Dufferin Peel Catholic District School Board, 19
2020-10-08, Dufferin Peel Catholic District School Board, 22
2020-10-09, Dufferin Peel Catholic District School Board, 22
2020-10-13, Dufferin-Peel Catholic District School Board, 24
2020-10-14, Dufferin-Peel Catholic District School Board, 22
2020-10-15, Dufferin-Peel Catholic District School Board, 29
2020-10-16, Dufferin-Peel Catholic District School Board, 32
2020-10-19, Dufferin-Peel Catholic District School Board, 31
2020-10-20, Dufferin-Peel Catholic District School Board, 36
2020-10-21, Dufferin-Peel Catholic District School Board, 39
2020-10-22, Dufferin-Peel Catholic District School Board, 39
2020-10-23, Dufferin-Peel Catholic District School Board, 42
2020-10-26, Dufferin-Peel Catholic District School Board, 44
2020-10-27, Dufferin-Peel Catholic District School Board, 49
2020-10-28, Dufferin-Peel Catholic District School Board, 48
2020-10-29, Dufferin-Peel Catholic District School Board, 47
2020-10-30, Dufferin-Peel Catholic District School Board, 45
2020-11-02, Dufferin-Peel Catholic District School Board, 46
2020-11-03, Dufferin-Peel Catholic District School Board, 47
2020-11-04, Dufferin-Peel Catholic District School Board, 42
2020-11-05, Dufferin-Peel Catholic District School Board, 44
2020-11-06, Dufferin-Peel Catholic District School Board, 43
2020-11-09, Dufferin-Peel Catholic District School Board, 41
2020-11-10, Dufferin-Peel Catholic District School Board, 44
2020-11-11, Dufferin-Peel Catholic District School Board, 51
2020-11-12, Dufferin-Peel Catholic District School Board, 53
2020-11-13, Dufferin-Peel Catholic District School Board, 57
2020-11-16, Dufferin-Peel Catholic District School Board, 56
2020-11-17, Dufferin-Peel Catholic District School Board, 54
2020-11-18, Dufferin-Peel Catholic District School Board, 54
2020-11-19, Dufferin-Peel Catholic District School Board, 54
2020-11-20, Dufferin-Peel Catholic District School Board, 55
2020-11-23, Dufferin-Peel Catholic District School Board, 56
2020-11-24, Conseil scolaire catholique MonAvenir, 57
2020-11-25, Conseil scolaire catholique MonAvenir, 50
2020-11-26, Conseil scolaire catholique MonAvenir, 56
2020-11-27, Conseil scolaire catholique MonAvenir, 54
2020-11-30, Conseil scolaire catholique MonAvenir, 56
2020-12-01, Conseil scolaire catholique MonAvenir, 64
2020-12-02, Conseil scolaire catholique MonAvenir, 64
2020-12-03, Conseil scolaire catholique MonAvenir, 65
2020-12-04, Conseil scolaire catholique MonAvenir, 71
2020-12-07, Conseil scolaire catholique MonAvenir, 73
2020-12-08, Dufferin-Peel Catholic District School Board, 69
2020-12-09, Conseil scolaire catholique MonAvenir, 72
2020-12-10, Conseil scolaire catholique MonAvenir, 67
2020-12-11, Conseil scolaire catholique MonAvenir, 69
2020-12-14, Conseil scolaire catholique MonAvenir, 65
2020-12-15, Conseil scolaire catholique MonAvenir, 68
2020-12-16, Conseil scolaire catholique MonAvenir, 68
2020-12-17, Conseil scolaire catholique MonAvenir, 74
2020-12-18, Conseil scolaire catholique MonAvenir, 69
2020-12-21, Conseil scolaire catholique MonAvenir, 70
2021-02-18, Peel District School Board, 4
2021-02-19, Dufferin-Peel Catholic District School Board, 8
2021-02-22, Dufferin-Peel Catholic District School Board, 13
2021-02-23, Dufferin-Peel Catholic District School Board, 16
2021-02-24, Dufferin-Peel Catholic District School Board, 18
2021-02-25, Dufferin-Peel Catholic District School Board, 21
2021-02-26, Conseil scolaire catholique MonAvenir, 28
2021-03-01, Conseil scolaire catholique MonAvenir, 30
2021-03-02, Conseil scolaire catholique MonAvenir, 40
2021-03-03, Conseil scolaire catholique MonAvenir, 42
2021-03-04, Conseil scolaire catholique MonAvenir, 43
2021-03-05, Conseil scolaire catholique MonAvenir, 43
2021-03-08, Conseil scolaire catholique MonAvenir, 42
2021-03-09, Conseil scolaire Viamonde, 43
2021-03-10, Conseil scolaire Viamonde, 45
2021-03-11, Conseil scolaire Viamonde, 48
2021-03-12, Conseil scolaire Viamonde, 48
2021-03-15, Conseil scolaire Viamonde, 49
2021-03-16, Conseil scolaire Viamonde, 45
2021-03-17, Conseil scolaire Viamonde, 52
2021-03-18, Conseil scolaire Viamonde, 57
2021-03-19, Conseil scolaire Viamonde, 60
2021-03-22, Conseil scolaire Viamonde, 61
2021-03-23, Conseil scolaire catholique MonAvenir, 69
2021-03-24, Conseil scolaire catholique MonAvenir, 67
2021-03-25, Conseil scolaire catholique MonAvenir, 65
2021-03-26, Conseil scolaire catholique MonAvenir, 69
2021-03-29, Conseil scolaire catholique MonAvenir, 72
The total number of student cases: 4036
Greatest total case is: 74
From the school: Conseil scolaire catholique MonAvenir

Would you prefer a bar graph of this data?
Type 'Yes' if you would like to proceed Otherwise, type 'No' or any key
```
The user can visual the data on a bar graph. 

![demo_covid19](https://user-images.githubusercontent.com/98615282/151627983-83693cc4-b736-414c-afc9-6ea99fb108aa.png)



