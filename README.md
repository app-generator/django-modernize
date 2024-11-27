# [Django Modernize](https://app-generator.dev/product/atlantis-dark/django/)

Open-source **Django** project crafted on top of **Modernize**, an open-source `Bootstrap 5` design from `AdminMart`.
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. `Modernize` has easy and intuitive responsive design whether it is viewed on retina screens or laptops.

- 👉 [Django Modernize](https://app-generator.dev/product/atlantis-dark/django/) - `Product Page`
- 👉 [Getting Started with Django](https://app-generator.dev/docs/technologies/django/index.html) - a `comprehensive tutorial`

<br />

> Features: 

- ✅ `Up-to-date Dependencies`
- ✅ Theme: [Django Admin Modernize](https://github.com/app-generator/django-admin-modernize), **designed by [AdminMart](https://adminmart.com/?ref=1)**
  - `can be used in any Django project` (new or legacy)
- ✅ **Authentication**: `Django.contrib.AUTH`, Registration
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

<br />

![Modernize - Bootstrap 5 design](https://user-images.githubusercontent.com/51070104/235424939-6b5b1d1d-0832-457a-82a9-599ba532da52.jpg)

<br />

## Manual Build 

> 👉 Download the code  

```bash
$ git clone https://github.com/app-generator/django-modernize.git
$ cd django-modernize
```

<br />

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Create the Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Codebase structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                            
   |    |-- settings.py                  # Project Configuration  
   |    |-- urls.py                      # Project Routing
   |
   |-- home/
   |    |-- views.py                     # APP Views 
   |    |-- urls.py                      # APP Routing
   |    |-- models.py                    # APP Models 
   |    |-- tests.py                     # Tests  
   |    |-- templates/                   # Theme Customisation 
   |         |-- includes                # 
   |              |-- custom-footer.py   # Custom Footer      
   |     
   |-- requirements.txt                  # Project Dependencies
   |
   |-- env.sample                        # ENV Configuration (default values)
   |-- manage.py                         # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Deploy on [Render](https://render.com/)

- Create a Blueprint instance
  - Go to https://dashboard.render.com/blueprints this link.
- Click `New Blueprint Instance` button.
- Connect your `repo` which you want to deploy.
- Fill the `Service Group Name` and click on `Update Existing Resources` button.
- After that your deployment will start automatically.

At this point, the product should be LIVE.

<br />

---
[Django Modernize](https://app-generator.dev/product/atlantis-dark/django/) - Minimal **Django** core provided by [App Generator](https://app-generator.dev).
