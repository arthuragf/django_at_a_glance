# Django Starter Project

![Django Logo](https://upload.wikimedia.org/wikipedia/commons/7/75/Django_logo.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Resources](#resources)

## Introduction

Welcome to the **Django Starter Project**! This repository serves as my first foray into Django, a high-level Python web framework that encourages rapid development and clean, pragmatic design. Through this project, I aim to explore Django's capabilities, understand its core concepts, and build a foundational understanding of web development using Django.

In this repository, you will find:

- A copy of **Django at a Glance** from the [official Django website](https://www.djangoproject.com/).
- Initial project setup files.

## Features

- **Django Overview:** Detailed insights from the official Django documentation to understand its core functionalities.
- **Basic Project Structure:** Initial setup to kickstart Django development.
- **Extensibility:** Prepared to add features such as models, views, templates, and more as I progress.

## Prerequisites

Before getting started, ensure you have the following installed on your system:

- **Python**: [Download Python](https://www.python.org/downloads/)
- **pip**: Python package installer (usually comes with Python)
- **Git**: Version control system (optional but recommended)

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/arthuragf/django_at_a_glance.git
   cd django_at_a_glance
   ```

2. **Create a Virtual Environment**

   It's good practice to use a virtual environment to manage project dependencies.

   ```bash
   python -m venv env
   ```

3. **Activate the Virtual Environment**

   - **Windows:**

     ```bash
     env\Scripts\activate
     ```

   - **macOS/Linux:**

     ```bash
     source env/bin/activate
     ```

4. **Install Django**

   ```bash
   pip install django
   ```

5. **Start a New Django Project**

   ```bash
   django-admin startproject mysite
   cd mysite
   ```

6. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

   Open your browser and navigate to `http://127.0.0.1:8000/` to see the Django welcome page.


## Resources

To assist with Django learning and development, here are some valuable resources:

- [Official Django Documentation](https://docs.djangoproject.com/en/stable/)
- [Django Getting Started Guide](https://docs.djangoproject.com/en/stable/intro/tutorial01/)
- [Django Girls Tutorial](https://tutorial.djangogirls.org/en/)
- [Real Python - Django Tutorials](https://realpython.com/tutorials/django/)