

# Todo App Django

This app is based Django framework. It consist of 3 pages, you can check them in screenshot section below.
This apps frontend is handled by Html, CSS , Bootstrap 5.0 along with djnago framework.
Backend is handled by djnago framework which is based on python. The Database creation ORM is automatically handled by django itself, by default Sqlite Database is there but you can change it manually if required.
## Deployment / Installation

To deploy this project you need following things installed.
- python 3 or above
- Django
- any IDE would be better i.e Pycharm, VS code


Open project folder in your IDE. To run this project do following.

change directory where projects manage.py is located, in case  of this project it would be 
```bash
  cd todo
```


check if you have django installed , if not then install django using pip in current directory. 
```bash
  pip install django
```

Apply migrations on your machine
```bash
   python manage.py makemigrations
   python manage.py migrate

```

Then runserver.
```bash
   python manage.py runserver

```

Then click on the link or copy the link from terminal in your browser.
It will be like this. copy the http link

```bash
   Starting development server at http://127.0.0.1:8000/

```

## Documentation

- [Django Documentation](https://docs.djangoproject.com/en/4.1/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Screenshots
### Home Page / Add tasks:
- This allows us to add tasks in database.
- There are two buttons such as add and delete which will redirect us to other two pages
![Add Task](https://github.com/bharat-ghadi/To_do_app/blob/main/screenshots/add%20task.PNG)
### Update Data:
- This allows us to update/modify task.
- we can also change task condition such completed or not, This will be reflected in main page.
- The styling is done by bootstrap classes i.e. form-label , form-control
![Update Task](https://github.com/bharat-ghadi/To_do_app/blob/main/screenshots/update%20task.PNG)
### Delete Task:
- This allows us to delete task.
- You can either proceed with deleting task or get to main page
![Delete Task ](https://github.com/bharat-ghadi/To_do_app/blob/main/screenshots/delete%20task.PNG)

## Support

For support, email bgaonkar96@gmail.com.


## FAQ

### Django sometimes throws error for bootstrap.

Answer : pip install django-bootstrap5
or relevent version you are trying

### manage.py : [Errno 2] No such file or directory
Answer : Change directory into your project where manage.py is located.




![Logo](https://github.com/bharat-ghadi/bharat-ghadi/blob/main/Beige%20Minimalist%20Profile%20LinkedIn%20Banner%20(1)_page-0001.jpg)
