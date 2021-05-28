# Django Base Project
Django is an excellent framework for easy and pragmatic website development. Many of its features come as pre-built elements or functions, saving us time.

However, we can further reduce our development time if we use templates for the development of solutions, and Django Base Project is the first of a series of templates developed by [Joël Gorin](https://github.com/joelgorin).
I hope it's useful.

## Table of Content
- [Before Start](##Before-Start)
    - [Requirements](###Requirements)
- [Clone this Repository](##Clone-this-Repository)
- [Create and Setup  Virtual Environment](##Create-and-Setup-Virtual-Environment)
- [Start Without Cloning](##Start-Without-Cloning)
    - [Settings](###Settings)
- [Create Apps](##Create-Apps)
- [Migrate Models](##Migrate-Models)
- [Running](##Running)

## Before Start
This project should be considered as a tutorial or template for Django projects. You are free to do whatever you want with the code in this repository.

For the development of this project, I used the best programming practices and I recommend continuing this practice.

### Requirements
Before you start, you must have the following items installed on your computer:
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to cloning this repository and make your own.
* [Python 3](https://www.python.org/downloads/) to code.
* [Virtualenv](https://pypi.org/project/virtualenv/) or an other tool for creating isolate environment.

## Clone this Repository
If you want use this project like a template, you can clone this project from [Github](https://github.com/joelgorin/django-base-project.git) following these steps:

```cmd
cd /path/to/workspace/folder
git clone https://github.com/joelgorin/django-base-project.git
```

or, you can download `.zip` file from the [Github repository](https://github.com/joelgorin/django-base-project.git).

## Create and Setup Virtual Environment

``` cmd
[Windows]
python -m venv env
.\env\Scripts\activate

[Linux]
python3 -m venv env
source ./env/bin/activate
```

## Start Without Cloning

``` cmd
[Windows and Linux]
pip install django
django-admin startproject settings .
```

### Settings

## Create Apps
It's a good practice create an `apps` package, to do this, follow these steps:

``` cmd
[Windows]
mkdir apps
cd apps
echo "" > __init__.py

[Linux]
mkdir apps
cd apps
touch __init__.py
```

To create an app, follow these steps:

``` cmd
[Windows and Linux]
cd apps
python ../manage.py startapp <app-name>
```

## Migrate-Models

## Running