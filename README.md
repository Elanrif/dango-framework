# Django Framework Tutorial

## Prerequisites

Before starting this tutorial, make sure you have the following installed on your system:

``````
- Python 3.x
- Django
- Django Rest Framework
``````


## Tutorial Content

The tutorial is divided into several parts, each covering a specific aspect of Django and Django Rest Framework. Here are the different sections:

1. [Serialization](https://www.django-rest-framework.org/tutorial/1-serialization/): This first tutorial introduces you to data serialization with Django Rest Framework.

(To be completed with the other parts of the tutorial)
### Tutorial 4
When that's all done we'll need to update our database tables. Normally we'd create a database migration in order to do that, but for the purposes of this tutorial, let's just delete the database and start again.
````
    1. rm -f db.sqlite3
    2. rm -r snippets/migrations
    3. python manage.py makemigrations snippets
    4. python manage.py migrate
````
    
##  In windows
 Remove-Item (alias rm ou ri in Linux) 


````
    1. del db.sqlite3 || Remove-Item db.sqlite3
    2. Remove-Item -Recurse -Force snippets\migrations
    3. python manage.py makemigrations snippets
    4. python manage.py migrate
````
## How to Use This Repository

To get started with this tutorial, simply follow the links to the different parts of the tutorial. Each part contains detailed instructions to help you understand and implement the discussed concepts.

## Author

This tutorial is maintained by [EL-anrif Said Baco](https://elanrif-portfolio.onrender.com/).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

