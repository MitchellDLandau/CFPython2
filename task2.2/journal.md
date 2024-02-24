# Django Project Set Up

## Learning Goals

Describe the basic structure of a Django project 

Summarize the difference between projects and apps

Create a Django project and run it locally

Create a superuser for a Django web application

### Suppose you’re in an interview. The interviewer gives you their company’s website as an example, asking you to convert the website and its different parts into Django terms. How would you proceed? For this question, you can think about your dream company and look at their website for reference. 
(Hint: In the Exercise, you saw the example of the CareerFoundry website in the Project and Apps section.)

If we were to be looking at a website like https://www.3x3custom.com a website about woodworking that has instructions and purchasable items we would consider the whole website the project. The individual parts like contact, shop, tutorials, home, cart are all examples of individual models in the whole project. 

### In your own words, describe the steps you would take to deploy a basic Django application locally on your system. 

You would first open a file and make a new virtual environment. 

Make sure django is installed in this environment. 

To initiate your new project your would use the command ```django-admin startproject <name>``` which would create the necessary files.

Starting from the source of the project you can use ```python manage.py migrate``` which I see as similar to building the project in other languages like Java. 

From here you can deploy the project using ```python manage.py runserver``` which will start up a local server to view the project. 

### Do some research about the Django admin site and write down how you’d use it during your web application development.

because the admin site gives you access to all of the CRUD operations this would be very useful during development. This would allow you to edit data and view the impacts of running your different models. Durring development you can see the impact of all of your functions and be able to track the flow of inormation from different parts of the application which can be difficult to visualize. 