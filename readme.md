Janelle Law & Jonathan Yan
## this repo is a clone of https://github.com/nelaturuk/education_pathways

### Home page
<img width="954" alt="image" src="https://user-images.githubusercontent.com/46268176/196266372-753e1986-e13c-4188-b195-3c5e5794c7e5.png">

### Results page - form
<img width="935" alt="image" src="https://user-images.githubusercontent.com/46268176/197051618-dae6deb6-3833-41ac-ad65-cfc4b6d49a60.png">

### Results page - results table
<img width="920" alt="image" src="https://user-images.githubusercontent.com/46268176/197042680-9463d7af-0877-499e-bfd0-1be46651da23.png">

### Low-fidelity prototype 1: Minor description page
<img width="960" alt="image" src="https://user-images.githubusercontent.com/46268176/196266013-5d77281a-9ded-4aa5-b503-902195be0706.png">

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
