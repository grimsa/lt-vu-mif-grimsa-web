class: center, middle, main-title

# This is a rough outline for the slides, but I had no slides that time.

---

# Software Engineering
Introductions and Course Overview

---
## Who are the teachers?

- Gediminas Rimša
    - Responsibility: lectures, exam
    - Email: [gediminas.rimsa@mif.vu.lt](gediminas.rimsa@mif.vu.lt)
--
- Virgilijus Krinickij
    - Responsibility: labwork, group project
    - Email: [virgilijus.krinickij@mif.vu.lt](virgilijus.krinickij@mif.vu.lt)

---
### Gediminas Rimša

- BSc and MSc of Software Engineering
--
- Primary field - software development
	- 9 years, 9 systems, 5 organizations
	- Software Developer / Architect / Tech Lead
--
- Secondary field - academia
	- 5 years
--
- Owner of a small software company
	- 2 years

---
### Virgilijus Krinickij

- Lecturer at Department of Computational and Data Modeling
- Member of [Cyber Security Laboratory](http://mif.vu.lt/lt3/apie-fakulteta/strukt%C5%ABra/informatikos-institutas/212-lt/institutai/informatikos/kib-saugumo-laboratorija/2475-ks-lab)
- Courses:
	- Software Engineering
	- Virtualization Basics
	- Network Security


---
### Kodėl viskas angliškai?

- Kursas pritaikytas ir Erasmus studentams
- Proga pasitobulinti specialybės anglų kalbą

---
### Kurso tikslas

- Klausimas: Kas yra "inžinerija"? 
	- Žaidžiat alias - ištraukiat žodį "inžinerija". Kaip aiškinat?
	- Su kuo siejasi?
		- Su tiltais, skrydžiais į kosmosą, "pushing the limit" technika, skardinėmis
		- Tour de france (wind tunnel, advanced data-driven strategies)

- Kitu kampu: Statybininkas vs 'statybų inžinerius'
	- Elektrikas vs "elektros tinklų inžinierius"
	- "hidroinžinierius"

---
## What is this course?

PSI - kitaip sakant inžinerijos taikymas PS kūrimui.

.center[This course is about **_engineering_** software.]

---
## What is this course?

> ## verb: engineer
> 1. design and build (a machine or structure).
>     - "the men who engineered the tunnel"
>
> 2. skilfully arrange for (something) to occur.
>     - "she engineered another meeting with him"
>
> -- <cite>Lexico</cite>

https://www.lexico.com/definition/engineer

---
## What is this course?

> ## verb: engineer
> 1.  to plan, build, or manage (something) by using scientific methods.
>     - "The system is engineered for maximum efficiency."
>
> 2. to produce or plan (something) especially in a clever and skillful way.
>     - "a brilliantly engineered plan"
>
> -- <cite>Merriam-Webster</cite>

https://www.merriam-webster.com/dictionary/engineer


---
## What is this course?

Problema: esame kokioje senovės visuomenėje ir mums reikia pertransportuoti kokį nors krovinį sausuma.

- "Visada vilkdavom, velkam ir nesukam galvos." (neprofesionalu)
- "Meistro X karučiai geriausi. Ir taškas." (neprofesionalu, laikomasi tiesos)
- "Esminė problema yra trintis. Riedėjimo trintis tipiškai mažesnė už slydimo trintį, dėl to karučiai su ratais dažniausiai pasiteisina. Kiek man teko susidurti, X pilnai patenkindavo panašiose situacijose kylančius reikalavimus, bet dėl kainos verta apsvarstyti ir pigesnes alternatyvas"

- This course covers only the basics of **_engineering_** software
	- Fundamental ideas and reasoning behind them
	- Rather than specific recipes

---
## Goal of this course

- Learn that building large software systems is not a mere matter of programming

- E.g. Bike shed / dog house vs. skyscraper / energy efficient house 

---
## Course format (VMA)

- Lectures
	- Reinforced by Reading Assignments
- Project
	- Supported by Consultations

---
### Course format: Lectures

- Every week
- Discuss essential ideas and practices
- Recorded
- Might have a guest speaker towards the end of the semester
- Different this year

### Course format: Reading Assignments

- Some will be mandatory, some optional
- Reinforce the concepts or broaden the understanding, connect different ideas

---

### Course format: Project (VMA)

- Whole semester
- Work in teams to build a software system
- Simulation of a real project
- Should give you both technical and social challenges

### Course format: Consultations

- Time dedicated every week
- Virgilijus acts as a mentor, customer, and technical supervisor
- Help you work on your projects
- Present intermediate deliveries and earn marks

---
## Grading (prezentuoti VMA)

- 60% - Project. Sum of:
	- 30% System specifications
		- At least half of this is a **_prerequisite_** for taking the exam
	- 20% System prototype
	- 10% Presentation
- 40% - Exam
	- In writing
	- Strictly individual, no resources
	- Covers both course material and your project
	- Not only recall the theory, but be able to reflect and apply it
	- Example will be provided


---
## Who are the students and their expectations?
(Based on 11 responses in the pre-course questionaire)

- Yra dirbančių, yra kūrusių nedidelės apimties sistemėles (dažnai minimas grupinis OOP projektas), yra besijaučiančių pradedančiaisiais
	- Skirtingas patirties lygis (įvardytas kaip iššūkis) - iššūkis, bet kartu ir galimybė mokytis vieniems iš kitų.
		 Mažiau suprantančiam gerai, nes padedamas greičiau išmoksta pagrindus; 
		 daugiau suprantančiam taip pat gerai, nes aiškindamas dalykus pats juos giliau supranti. 
		 Taip pat galima pasitobulinti mentorystės įgūdžius, kurie būtini patyrusiems specialistams bei komandų vadovams.
		- Ypač tiem, kas esate sukūrę dalykų vieni, bet nesate dirbę komandose.
	- Iššūkiai: Learning new languages, reinventing the wheel (learning what is available)
	- Darbas nuotoliniu būdu - iššūkis, bet kartu ir galimybė atrasti efektyvesnius bendradarbiavimo būdus
	- Iššūkis time management/motivation

- Aspirations
	- Almost all of the respondents see themselves working with code or related artifacts in the future
		- Software development
		- System administration
		- Testing
		- Cybersecurity
	- Interests
		- Working with databases
		- Game development
		- Website development

- Prior expectations about the course
	- Nothing specific yet
	- Some have read the course description, but nobody has heard any prior reviews

- Topics
	- Good/Bad/Best practices  						// sidenote - "There is no such thing as "best practice" -  https://www.satisfice.com/blog/archives/5164
	- Most wanted languages
	- Optimizations / micro optimisations
	- Project planning
	- Documentation and readability

- What would make this a better course?
	- More practical tasks. Theory is overrated.
	- More interaction with the students (pandemic was unexpected)


---


Near-term plan:
	- Start fast, minimum info to get you up and running towards zero-feature release
	- Extra lecture next week?



---
class: middle, center
# Questions?

---

## Next
- Introduction to Software Engineering