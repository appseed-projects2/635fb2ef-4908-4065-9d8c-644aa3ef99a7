# [Datta Able Django](https://appseed.us/product/datta-able/django/)

Open-source **Django Dashboard** generated by `AppSeed` op top of a modern design. **[Datta Able](https://appseed.us/product/datta-able/django/)** Bootstrap Lite is the most stylised Bootstrap 4 Lite Admin Template, around all other Lite/Free admin templates in the market. It comes with high feature-rich pages and components with fully developer-centric code. Before developing Datta Able our key points were performance and design.

- 👉 [Datta Able Django](https://appseed.us/product/datta-able/django/) - `Product page`
- 👉 [Complete documentation](https://docs.appseed.us/products/django-dashboards/datta-able) - `Learn how to use and update the product`
- 🚀 Free [support](https://appseed.us/support/) for **registered users** (Email & `Discord`) 

<br />

> Built with [App Generator](https://appseed.us/generator/), timestamp `2022-10-17 02:43`

- `Up-to-date dependencies`
- Database: `mysql`
- UI-Ready app, Django Native ORM
- `Session-Based authentication`, Forms validation
- `Dark Mode` (enhancement)
  - Persistent via browser `local storage`
  
<br />

![Datta Able (enhaced with dark mode) - Open-Source Seed project generated by AppSeed.](https://user-images.githubusercontent.com/51070104/176118649-7233ffbc-6118-4f56-8cda-baa81d256877.png)

<br />




## ✨ Set up the MySql Database

**Note:** Make sure your Mysql server is properly installed and accessible. 

> **Step 1** - Create the MySql Database to be used by the app

- `Create a new MySql` database
- `Create a new user` and assign full privilegies (read/write)

<br />

> **Step 2** - Edit the `.env` to match your MySql DB credentials. Make sure `DB_ENGINE` is set to `mysql`.

- `DB_ENGINE`  : `mysql` 
- `DB_NAME`    : default value = `appseed_db`
- `DB_HOST`    : default value = `localhost`
- `DB_PORT`    : default value = `3306`
- `DB_USERNAME`: default value = `appseed_db_usr`
- `DB_PASS`    : default value = `pass`

<br />

Here is a sample:  

```txt
# .env sample

DB_ENGINE=mysql             # Database Driver
DB_NAME=appseed_db          # Database Name
DB_USERNAME=appseed_db_usr  # Database User
DB_PASS=STRONG_PASS_HERE    # Password 
DB_HOST=localhost           # Database HOST, default is localhost 
DB_PORT=3306                # MySql port, default = 3306 
```

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/635fb2ef-4908-4065-9d8c-644aa3ef99a7.git
$ cd 635fb2ef-4908-4065-9d8c-644aa3ef99a7
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />



## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like bold elements and beautiful websites, **Datta Able** is the most stylish Bootstrap 4 Admin Template compare to all other Bootstrap admin templates. It comes with high feature-rich pages and components with fully developer-centric code. 

- 👉 [Django Datta PRO](https://appseed.us/product/datta-able-pro/django/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Datta Able PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/170474361-a58da82b-fff9-4a59-81a8-7ab99f478f48.png)

<br />

---
[Datta Able Django](https://appseed.us/product/datta-able/django/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
