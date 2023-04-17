#### Case Study - 1

Suppose you are given the following requirements for a simple database for the National Hockey League (NHL):
1. the NHL has many teams,
2. each team has a name, a city, a coach, a captain, and a set of players, each player belongs to only one team,
3. each player has a name, a position (such as left wing or goalie), a skill level, and a set of injury records,
4. a team captain is also a player,
5. a game is played between two teams (referred to as host_team and guest_team)and has a date (such as May 11th, 1999) and a score (such as 4 to 2).

Construct a clean and concise ER diagram for the NHL database.




#### Case Study - 2
A university registrar’s office maintains data about the following entities:

1. courses, including number, title, credits, syllabus, and prerequisites;
2. course offerings, including course number, year, semester, section number,
instructor(s), timings, and classroom;
3. students, including student-id, name, and program;
4. instructors, including identi-cation number, name, department, and title.

Further, the enrollment of students in courses and grades awarded to students in each course they
are enrolled for must be appropriately modeled. Construct an E-R diagram for the registrar’s
of-ce.Document all assumptions that you make about the mapping constraints.



#### Case Study - 3
1. Construct an E-R diagram for a car-insurance company whose customers own one or more cars each. 

2. Each car has associated with it zero to any number of recorded accidents.

Construct appropriate tables for the above ER Diagram.



#### Case Study - 4
1. Construct an E-R diagram for a hospital with a set of patients and a set of medical doctors.
2. Associate with each patient a log of the various tests and examinations conducted.


#### Case Study - 5
Consider a database used to record the marks that students get in different exams of different
course offerings.
1. Construct an E-R diagram that models exams as entities, and uses a ternary relationship, for
the above database.

2. Construct an alternative E-R diagram that uses only a binary relationship between students
and course-offerings. 

Make sure that only one relationship exists between a particular student
and course-offering pair, yet you can represent the marks that a student gets in different exams of
a course offering.

#### Case Study - 6
Design an E-R diagram for keeping track of the exploits of your favorite sports team. 
1. You should store the matches played, 
2. the scores in each match, the players in each match and
3. individual player statistics for each match. 
4. Summary statistics should be modeled as derived
attributes.