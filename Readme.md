# Django Template

This template is for use to kick in fast into a Django Project.

## Getting Started

---

**Fork Repository**

```
Press the fork button in top-right corner
```

**Clone repository**

```sh
$ git clone "https://username.github.io/Django-Template
```

**Making Virtual Environment**

```
python3 -m venv <name>
```

**Activating virtual environment**

```sh
Linux $ source <name>/bin/activate
Windows > source <name>/Scripts/activate
```

**Installing required python packages**

> Navigate to requirements folder in the root directory

```sh
pip install -r base.txt
```

**Install Postgresql, Create a User and Database. Also, grant all privileges of that db to User**

```sh
Linux
$ sudo apt install postgresql postgresql-contrib
$ sudo -u postgres psql

Windows
http://www.postgresqltutorial.com/install-postgresql/
```

```
CREATE DATABASE yourdbname;
CREATE USER youruser WITH ENCRYPTED PASSWORD 'yourpass';
GRANT ALL PRIVILEGES ON DATABASE yourdbname TO youruser;
```

> Create a .env file based on env.example in root directory changing the database credentials and leave other fields as it is.

**Creating Django SuperUser**

```sh
$ python manage.py createsuperuser
```

**Implementing Database**

```sh
$ python manage.py migrate
```

## Contributing Guidelines

---

---

- Fork the repository

- Clone the repository with

```sh
$ git clone "https://github.com/username/Django-Template.git
```

- Create a branch to work upon

```sh
$ git checkout -b branchname
```

- Add your changes and commit them

```sh
$ git add -A
$ git commit -m"meaningful commit message"
```

- Push your changes to your forked copy

```sh
$ git push origin master
```

- Make a Pull Request

---
