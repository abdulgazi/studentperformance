# studentperformance
Erin Sutton
Abdul Raheman Nasir Gazi

Goal: Does a students circumstances affect their final score in portuguese?

The files assume that the data is in the same directory as the python files, if it is not a
relaitive file path will be required. After going though the data cleaning process the data
was found to be already clean, as such there is a seperate file for each part of the
assignment for readability and to be clear where each part begins and ends.

Attributes:
4: Address
6: Pstatus
12: Guardian
13: Traveltime
23: Romantic
24: Famrel
28: Walc
29: Health
30: Absences
33: Final Grade

Spliting the grade data:
target:
0 : 0 =< grade < 5
1: 5 =< grade < 10
2: 10 =< grade < 15
3: 15 =< grade < 20

address:
0 = R
1 = U

pstatus:
 0 = A
 1 = T
 
guardian:
0 = mother
1 = father
2 = other

romantic:
0 = no
1 = yes
