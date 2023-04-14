# first_wagtail_website


## Run Locally

Let's check the whether we have an appropriate version of Python 3:

```bash
  python --version
```
![alt text](https://github.com/VG-1/first_wagtail_website/blob/main/images/1.png)

Create and activate a virtual environment

```bash
  py -m venv mysite\env
mysite\env\Scripts\activate.bat
# or:
mysite\env\Scripts\activate
```

Install Wagtail

```bash
  pip install wagtail
```

Generate your site

```bash
  wagtail start mysite mysite
```
Install project dependencies

```bash
  cd mysite
  pip install -r requirements.txt
```
Create the database

```bash
    python manage.py migrate
```
Create an admin user

```bash
    python manage.py createsuperuser
```
Start the server

```bash
python manage.py runserver
```
If everything worked well, we will have our site running on http://127.0.0.1:8000/ 
