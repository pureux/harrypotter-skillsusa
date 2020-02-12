# Harry Potter Sorting Hat - Skills USA

A programming exercise based on the plot of the Harry Potter franchise, specifically regarding the Sorting Hat and incoming students to Hogwarts.

The requirements are below.  Test your skills to see what you can build.

## Requirements

You're a programmer, Terry!  20 incoming students received invitation letters to Hogwarts and are gathered in the banquet hall to be sorted into their houses.

### Phase 1

Seed the application with 20 incoming Hogwarts students (names provided below), in the order provided.

Program a Sorting Hat algorithm to sort the students evenly into the four houses (five students per house) and display the resulting list of students alphabetically (A to Z) by the student's name, grouped by their respective house.

*Note: For phase 1, it does not matter in which house a particular student is sorted.*

#### Seed Data


| House |
| ------ |
| Gryffindor |
| Hufflepuff |
| Ravenclaw |
| Slytherin |

---

| ID | Student |
| -- | ------- |
| 01 | Sam Roots |
| 02 | Wayman Fledgling |
| 03 | Lyle Falcon |
| 04 | Ada Dogwood |
| 05 | Phillip Filly |
| 06 | Alberto Fern |
| 07 | Oak Cobweb |
| 08 | Alfalfa Nightshade |
| 09 | Frost Cycad | 
| 10 | Birch Slumber |
| 11 | Thyme Rubble |
| 12 | Jo Marble |
| 13 | Taylor Hatch |
| 14 | Clem Beetle |
| 15 | Eli Barrows |
| 16 | Snow Lambkins |
| 17 | Delta Cups |
| 18 | Breeze Littletree |
| 19 | Shell Bags |
| 20 | Azure Soots |

### Phase 2

After ensuring you have a successful and complete solution for Phase 1, enhance your Sorting Hat algorithm to take qualities into account when determining to which house a student should be assigned.

Use the updated seed data below, in the order provided, to seed the 20 students with each student having three total qualities valued by houses at Hogwarts.

Sort the students into the house that matches two or more of the student's qualities. Display the resulting list of students alphabetically (A to Z) by the student's name, grouped by their respective house.

#### Updated Seed Data

| House | Qualities |
| ----- | --------- |
| Gryffindor | courage<br/>bravery<br/>nerve<br/>chivalry |
| Hufflepuff | hard work<br/>patience<br/>justice<br/>loyalty |
| Ravenclaw | intelligence<br/>creativity<br/>learning<br/>wit |
| Slytherin | ambition<br/>cunning<br/>leadership<br/>resourcefulness |

> Reference: [Hogwarts Wikipedia](https://en.wikipedia.org/wiki/Hogwarts)

---

| ID | Student | Qualities | Expected House |
| -- | ------- | --------- | -------------- |
| 01 | Sam Roots | ambition<br/>courage<br/>bravery | Gryffindor |
| 02 | Wayman Fledgling | courage<br/>patience<br/>loyalty | Hufflepuff |
| 03 | Lyle Falcon | ambition<br/>leadership<br/>justice | Slytherin |
| 04 | Ada Dogwood | creativity<br/>intelligence<br/>hard work | Ravenclaw |
| 05 | Phillip Filly | learning<br/>ambition<br/>intelligence | Ravenclaw |
| 06 | Alberto Fern | patience<br/>loyalty<br/>nerve | Hufflepuff |
| 07 | Oak Cobweb | chivalry<br/>courage<br/>resourcefulness | Gryffindor |
| 08 | Alfalfa Nightshade | cunning<br/>wit<br/>ambition | Slytherin |
| 09 | Frost Cycad | hard work<br/>creativity<br/>justice | Hufflepuff |
| 10 | Birch Slumber | learning<br/>creativity<br/>chivalry | Ravenclaw |
| 11 | Thyme Rubble | leadership<br/>cunning<br/>patience | Slytherin |
| 12 | Jo Marble | nerve<br/>justice<br/>chivalry | Gryffindor |
| 13 | Taylor Hatch | ambition<br/>bravery<br/>courage | Gryffindor |
| 14 | Clem Beetle | chivalry<br/>hard work<br/>loyalty | Hufflepuff |
| 15 | Eli Barrows | ambition<br/>creativity<br/>leadership | Slytherin |
| 16 | Snow Lambkins | courage<br/>leadership<br/>resourcefulness | Slytherin |
| 17 | Delta Cups | intelligence<br/>wit<br/>patience | Ravenclaw |
| 18 | Breeze Littletree | patience<br/>loyalty<br/>leadership | Hufflepuff |
| 19 | Shell Bags | intelligence<br/>nerve<br/>creativity | Ravenclaw |
| 20 | Azure Soots | bravery<br/>intelligence<br/>chivalry | Gryffindor |

### Phase 3

After ensuring you have a successful and complete solution for Phase 2, enhance your code to allow the end user to add more students, with three qualities each, and sort them with the initial 20 students appropriately.

Require three qualities per student. Each quality must match a quality from a house.  Do not allow multiples of the same quality for the same student.  Require a student name to be entered.  Do not allow the student name to match an existing student.

Then allow the end user to re-assign an existing student to a different house.

Then allow the end user to expel a sorted student from Hogwarts (remove them from all houses).
