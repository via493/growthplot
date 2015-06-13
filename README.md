# growthplot

Project for App4Kids Hackathon

This project uses Python's Django web framework on top of a PostgreSQL database. Ensure that you have Python and Postgres installed on your computer. You should be able to get all OS specific installation instructions for Python and Postgres by visitng the relevant websites.

##Installation instructions for Django 1.8:
To install Django you can use Python's package manager `pip`:
* If you're using MacOSX or Linux, in your terminal you can use the command `sudo pip install Django` to install the framework in your Python's installation directory.
* [This page](https://docs.djangoproject.com/en/1.8/topics/install/#installing-official-release) has more specifc installation instructions for your particular OS (for example if you're using Windows)
* You can check if Django successfully installed by entering `$ python -c "import django; print(django.get_version())"` in your terminal. You should see your currently installed version of Django at the prompt. If Django did not successfully install you will see a message like `“No module named django”`

##Hooking in Postgres
By default Django uses an SQLite database for backend storage. We've opted to use PostgreSQL since it is more robust and offers a vareity of useful features as the dataset grows. You will need to install the `Psycopg` adapter for Django to hook into a Postgres database.
* You can use `pip` to install the adapter using the the command `$ pip install psycopg2` in your terminal.
* Consult [this page](http://initd.org/psycopg/docs/install.html) for your OS specific installation instructions.
