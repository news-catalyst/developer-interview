# News Catalyst Developer Interview

## Quickstart

### Prerequisites

To setup this basic Django application, make sure you have Python 3 and pipenv installed on your machine. If you're on a Mac, I recommend [these instructions](https://wsvincent.com/install-python3-mac/). Please let me know if you have trouble installing these requirements.

### Installing the application

To work on this repository, first clone it to your machine and install the requirements.

```
$ git clone https://github.com/news-catalyst/developer-interview
$ pipenv install
$ pipenv run python manage.py migrate
$ pipenv run python manage.py runserver
```

## What you will do

### Pre-interview

Before our interview, you will need to write some code on your own setting up the basic structure of this app. When writing your solution, feel free to go in any direction you see fit, as long as your solution matches the requirements below. That means you can install any libraries you want or use any programming style you want. The goal is to demonstrate how you write code from scratch.

Here are the tasks. Implement the following features on your fork:

1. In the users app, build models that:
  - Attach a profile to Django's built-in user model
  - Allow users to associate multiple email addresses with their account
  - Allow users to upload a profile image (just the model, don't worry about actually handling an upload)
  - Allow users to enter a short biography about themselves

2. In the organizations app, build models that:
  - Establish organizations with unique names
  - Allow users to be members of organizations
  - Allow certain users to be administrators of that organization

3. Implement a view and template that displays all the users in the database.

### Interview

In the interview, we will do two things:

1. Review the code you did in the pre-interview step. Be prepared to talk through the architectural decisions you made.
2. Together, we will edit the view and template you built to display to show the organizations they are affiliated with.

## Questions/concerns

Email tyler@newscatalyst.org if you have issues installing the application or have questions about the tasks.
