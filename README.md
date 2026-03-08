# My SWE assign.2

[![Build Status](https://app.travis-ci.com/hvp2015/swe1-app.svg?branch=main)](https://app.travis-ci.com/hvp2015/swe1-app)
[![Coverage Status](https://coveralls.io/repos/github/hvp2015/swe1-app/badge.svg?branch=main)](https://coveralls.io/github/hvp2015/swe1-app?branch=main)

## About
A Django web application for SWE assign.2.

## Setup

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Running Tests

```bash
python manage.py test
```

## CI/CD
This project uses Travis CI for continuous integration and deploys to AWS Elastic Beanstalk on successful builds.
