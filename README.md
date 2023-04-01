# Django-API-Rest-Framework

Week 10 is free or no homework. Week 11 is test 2. The last iteration will be taught in week 12.

Each student is assigned a problem calculated according to the formula code % 3 + 1, where code is the code in the list of grades. It must be handed in:

Math-info and Physics-info
Tests and specifications in all iterations.

Iteration 1

All CRUDs, minimum one more different CRUD functionality. With validations, layered architecture with all elements described in the course. Saving data to files.
No PEP 8 warnings. These will be displayed on github when you commit. Maximum grade if there are PEP 8 warnings is 9.

Iteration 2
All functionality except Undo+Redo.
Generic repository, own exception classes.
Use type hinting, ABC, protocol.
No PEP 8 warnings. These will be displayed on github when you commit. Maximum score if there are PEP 8 warnings is 8.

Iteration 3
Implemented Undo+Redo efficiently.
Refactored all possible functionality using map, filter, list comprehensions, reduce, filter.
Refactored minimum one method using recursion.
Refactored minimum two methods using lambda.

Implemented and used a proprietary sort function that has the same interface as Python's sorted function.

No PEP 8 warnings. These will be displayed on github when committing. Maximum score if there are PEP 8 warnings is 7.

Bonuses: awarded as grades above 10.

Agile documentation, according to https://asana.com/guide/examples/project-management/asana-agile. Other tools can be used as long as the same concepts are kept. Maximum 5p / iteration.

Application writing in Django with databases, keeping as much as possible the organization from the course. Maximum 7p / iteration.

Writing the application in Angular or React with Material or Bootstrap, keeping as far as possible the organisation from the course. Maximum 10p / iteration.
Writing the application as REST API in Django with database and in Angular or React with Material or Bootstrap as frontend. Grade 10 on the lab and practical exam. You are required to show progress during iterations if you choose this bonus. Partial bonuses commensurate with the above may be given for apps that are functional but do not follow the development principles of such apps.

Car service
3.1. CRUD car: id, model, year of purchase, no. km, under warranty. Km and year of purchase to be strictly positive.

3.2. CRUD customer card: id, name, surname, CNP, date of birth (dd.mm.yyyy), date of registration (dd.mm.yyyy). The CNP must be unique.
Transaction CRUD: id, machine_id, customer_card_id (can be null), parts amount, labour amount, date and time. If there is a customer card, then apply a 10% discount for the labour. If the machine is under warranty, then parts are free. Print the price paid and the discounts granted.

3.4. Machine and customer search. Full text search.

3.5. Display all transactions with the amount in a given range.

3.6. Display machines sorted in descending order by amount obtained per job.

3.7. Display customer cards sorted descending by the amount of discounts obtained.

3.8. Deleting all transactions in a given day range.

3.9. Updating the warranty on each car: a car is under warranty if and only if it has a maximum of 3 years from purchase and a maximum of 60 000 km.


