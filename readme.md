# ECE444-F2021-Lab3
### Alexander Senn
### This repo is a clone of https://github.com/nelaturuk/education_pathways.

#### Activity 1:
![A1](screenshots/A1.png)

#### Activity 2:
![A2](screenshots/A2.png)

#### Activity 3:
![A3](screenshots/A3.png)

#### Activity 4:
![A4-1](screenshots/A4-1.png)
![A4-2](screenshots/A4-2.png)

#### Activity 5:
##### Functional Requirement: Search for courses
Currently the search uses a rudimentary algorithm to predict and match search terms with courses, but it is not very robust and doesn't work with prefixes. For example, it doesn't perform as expcted when searching "ECE4". This should be improved by reworking the search algorithm to better deal with all the metadata associated with each course.
##### Non-functional Requirement: Usability
The current interface is not very intuitive. It should present the search results in a more readable layout and provide search tools in more intuitive and flexible ways. For example, through the use of differentiating UI elements, required and non required fields should be made clear to the user, allowing the user to more quicky input search queries.




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
