### NOTE: Please note that this repo is a clone of https://github.com/nelaturuk/education_pathways for the first project of the University of Toronto's ECE444 Software Engineering course ###

## Screenshots

Activity 1:

![alt text](https://github.com/crystalmdsouza/ECE444-F2021-Lab3/blob/main/lab%203%20part%201%20image%201.png)

Activity 2:

![alt text](https://github.com/crystalmdsouza/ECE444-F2021-Lab3/blob/main/lab%203%20part%202%20image%201.png)

Activity 3:

![alt text](https://github.com/crystalmdsouza/ECE444-F2021-Lab3/blob/main/lab%203%20part%203%20image%201.png)

Activity 4:

![alt text](https://github.com/crystalmdsouza/ECE444-F2021-Lab3/blob/main/lab%203%20part%204%20image%201.png)
![alt text](https://github.com/crystalmdsouza/ECE444-F2021-Lab3/blob/main/lab%203%20part%204%20image%202.png)

Activity 5:

Upon reviewing the Education Pathways website content, I noted that one functional requirement is the ability to return a list of courses that is relevant to a student's needs. It is the main focus of the website, and there are many non-functional requirements supporting it, like allowing search by interest and filtering by department, year of study, and campus. One way I can better satisfy the functional requirement is by adding the ability to filter search results by degree requirement that the list of course fulfills (ie. accreditation units for engineers, breadth areas for arts and science students) so that students have an easier time finding a course that supports them towards graduation. One way I can improve the non-functional requirement of searching by interest is by adding the ability to return course lists without a search term - sometimes students may want to see all courses within a certain year of study, department and campus without constraining results by interest.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
