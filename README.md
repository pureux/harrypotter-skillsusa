# Harry Potter Sorting Hat - Skills USA Programming Competition

A programming exercise based on the plot of the Harry Potter franchise, specifically regarding the Sorting Hat and incoming students to Hogwarts.

The requirements are below.  Test your skills to see what you can build.

## Requirements

Incoming students received invitation letters to Hogwarts and are gathered in the banquet hall to be sorted into their houses.  Complete the following three phases to help the Sorting Hat group the students.  Get as far as you can while still having working, separate solutions for each previous phase.

### Phase 1

Seed the application with 20 incoming Hogwarts students (names provided below), in the order provided.

Program a Sorting Hat algorithm to sort the students evenly into the four houses (five students per house) and display the resulting list of students alphabetically (A to Z) by the student's first name, grouped by their respective house.

*Note: For phase 1, it does not matter in which house a particular student is sorted.*

#### Seed Data

##### Houses

| House |
| ------ |
| Gryffindor |
| Hufflepuff |
| Ravenclaw |
| Slytherin |

##### Students

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

Sort the students into the house that matches two or more of the student's qualities. Display the resulting list of students alphabetically (A to Z) by the student's first name, grouped by their respective house.

#### Updated Seed Data

##### Houses

| House | Qualities |
| ----- | --------- |
| Gryffindor | courage<br/>bravery<br/>nerve<br/>chivalry |
| Hufflepuff | hard work<br/>patience<br/>justice<br/>loyalty |
| Ravenclaw | intelligence<br/>creativity<br/>learning<br/>wit |
| Slytherin | ambition<br/>cunning<br/>leadership<br/>resourcefulness |

> Reference: [Hogwarts Wikipedia](https://en.wikipedia.org/wiki/Hogwarts)

##### Students

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

## Scoring Criteria

```
Does it Work                       200
Completeness                        50
Correctness of Output               50
Code Clarity/Documentation          50
Structure/Quality of Work           50
Efficiency of Code                  40
Phase 2                             30
Phase 3                             30
Interview                            0 to -30
Clothing/Appearance                  0 to -30
Resume                               0 to -30
TOTAL                              500
```

---

# Harry Potter New House Petition - Skills USA Web Design Competition

A web design exercise based on the Harry Potter franchise, extending the storyline by promoting the creation of new house (group) for students at Hogwarts.

The requirements are below.  Test your skills to see what you can build.

## Requirements

The Sorting Hat has had trouble sorting some of the incoming students again this year, and a group of second year students has petitioned for the creation of a new house (aka group) to accompany Gryffindor, Hufflepuff, Ravenclaw, and Slytherin at Hogwarts.

Hagrid has found a suitable and available dormitory on the grounds of Hogwarts with adequate housing, access to common areas, within walking (or broom riding) distance from the classrooms.

Come up with and incorporate the following unique attributes for the new house:

* Name
* Qualities it values (4 of them)
* Emblem (typically an animal)
* Colors (1 primary and 1 accent)

These should be both representative and visually appealing, but also distinct from the other four houses.

For reference:

| House | Qualities | Emblem | Color |
| ----- | --------- | ------ | ----- |
| Gryffindor | courage<br/>bravery<br/>nerve<br/>chivalry | lion | red and yellow |
| Hufflepuff | hard work<br/>patience<br/>justice<br/>loyalty | badger | yellow and brown |
| Ravenclaw | intelligence<br/>creativity<br/>learning<br/>wit | raven | blue and gray |
| Slytherin | ambition<br/>cunning<br/>leadership<br/>resourcefulness | snake | green and gray |

Design your own logo (aka crest) using the emblem you decided on, matching the general theme and style of other house logos at Hogwarts (it does not have to be as detailed as those used in the movie).

Design and implement a web site for your new Hogwarts house, incorporating your new logo, color scheme, and other house attributes.

Include separate pages (as well as navigation) for:

| Page | Content |
| ---- | ------- |
| Home | News content and a brief call to action for why the new house should be created |
| About | General content about the new house, as well as a Google map or other interaction map visualization to depict the house's dormitory location at Hogwarts (pick a location in Europe to visualize, and ideally have the map zoomed in to a specific area of a large building/complex) |
| Sign the Petition | A form for the user to fill out that submits their name, email address, and optional comments, including validation of required fields and email address format |

Your web site should be responsive for mobile phones, tablets, and desktops/laptops.  It should be cross-browser compatible and meet W3C standards. It should meet the WCAG accessibility guidelines.

You *can* use the Internet, including graphic design resources and images you find on the web.  However, the house name, logo, color scheme, and qualities valued must be unique and cannot be copied from existing work.

You *cannot* use frameworks, libraries, or similar tools (examples: Bootstrap, Tailwind, jQuery, React, Vue, Angular, etc.).  If you are unsure about something, ask one of the judges.

## Scoring Criteria

```
Does it Work                       125
Completeness                        75
Structure/Quality of Work           50
Design, Logo, and Branding          50
Intuitive Navigation and Flow       40
Content Formatting and Readability  40
Accessibility                       40
Responsiveness to Screen Size       40
Cross Browser Support               40
Interview                            0 to -30
Clothing/Appearance                  0 to -30
Resume                               0 to -30
TOTAL                              500
```
