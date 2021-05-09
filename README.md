# College_Administration_System

This Python project has been  developed using Django, a Python-based open-source web framework. The system will have various features such as Login and Sign up, detailed view of courses, delete or add courses, different access rights to users. I developed this project using Django, It is an open-source Python-based web framework with a lot of inbuilt functionalities like UserCreationforms, login, and many more.

I used  the following technologies:
Python
HTML
CSS
Bootstrap
Django framework

I have created 4 pages in this project:
   
   1> Home: It deals with the home page request for both the users (college staff and the student). It renders all the ‘course’ objects to home.html              which displays all the details of the course and also checks whether the user is authenticated or not and displays everything based on its            access rights.
   
   2> Create_Course: If the user has access rights (admin) then it will create new courses using the CourseForm object otherwise it will redirect the                      user to home page.
   
   3> Delete_Course: It first checks whether the user is authenticated or not. If the user is not authenticated (i.e. a student) then he cannot delete                      a course from the website, so it will redirect the user back to the home page. After checking the authenticity it allows deletion                      of the course.
   
   4> Description: It redirects the user to a description page which contains all the information of the requested course. 
   
    (Rest are register, login, and logout which use inbuilt django functions.)
    
To install the library, you can use the pip installer from cmd/terminal.
`pip install Django`
