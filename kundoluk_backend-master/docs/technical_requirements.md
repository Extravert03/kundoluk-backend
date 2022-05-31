# 1. Project purposes
The main purpose is to develop modern studying platform for school students.

It is not for commercial using.
Project will be hosted on Heroku, because it is just my pet-project.

# 2. Functionality
This project includes following functionality:
- Authorization - implemented via JWT tokens.
- E-Diary - the platform where students (and their parents) can observe progress in their studies. Whereas teachers can manage the information about progress of students.
- Public API for users - in [system](https://kundoluk.edu.kg/) that we now use, we have no API. So I had to write own library for scraping information from there, which is not convenient.

# 3. Technology stack (back-end)
- Django Rest Framework