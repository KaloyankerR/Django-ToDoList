# ToDo list
You login or register as a user in this project. Each user has their own tasks, which aren't visible for the others.
All tasks can be managed with the help of the CRUD operations and the Django amdmin site. Also you get the option to drag the tasks, so that you can order them as you wish.
Users can mark a task as completed or not completed, which will result in changing the circle in front of the task title to green. 
Another functionality of the project is that users can search for their task with the search tab.

<!-- ABOUT THE PROJECT -->
## About The Project

### Login page
![Login Page Screen Shot][login-page-screenshot]

### Register page
![Register Page Screen Shot][register-page-screenshot]

### Tasks page (aka home page)
![Tasks Page Screen Shot][tasks-page-screenshot]

### Add&Update page
![Add&Update Page Screen Shot][add-update-page-screenshot]

### Built With
* [![Python][Python]][Python-url]
* [![Django][Django]][Django-url]
* [![Jinja][Jinja]][Jinja-url]

<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple example steps.

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/KaloyankerR/Django-ToDoList.git 
   ```
2. Install Django
   ```sh
   pip install django
   ```
3. Navigate to the main project folder
   ```sh
   cd .\todo_list\
   ```
4. In order to run it, open a terminal in your locat repository and type
   ```sh
   python .\manage.py runserver
   ```
5. Create a super user with running the commands
    ```sh
    python3 manage.py createsuperuser
    ```
or just fill in the register page

<!-- USAGE EXAMPLES -->
## Usage
The project can be used in many ways. The main is to track your tasks.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
I've included a few of my favorites to kick things off!

* [Dennis Ivanov's website](https://www.dennisivy.com/)
* [Django views](https://ccbv.co.uk/)
* [Django's documentation](https://docs.djangoproject.com/en/4.1/)
* [Jinja's documentation](https://jinja.palletsprojects.com/en/3.1.x/)
* [W3schools tutorial on Django](https://www.w3schools.com/django/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[login-page-screenshot]: /photos/login.PNG
[register-page-screenshot]: /photos/register.PNG
[tasks-page-screenshot]: /photos/tasks.PNG
[add-update-page-screenshot]: /photos/addUpdate.PNG
[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/
[Django]: https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white
[Django-url]: https://www.djangoproject.com/
[Jinja]: https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black
[Jinja-url]: https://jinja.palletsprojects.com/en/3.1.x/
