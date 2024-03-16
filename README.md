## Overview

Docops is a comprehensive document management system aimed at enhancing productivity in the workplace. It provides a robust solution for managing, organizing, and sharing documents within an organization.

## Features

Centralized Document Repository: Offers a single source of truth for all organizational documents.
Advanced Search and Organization: Easily find documents with powerful search and tagging capabilities.
Access Control: Define who can view, edit, or share documents to ensure security and confidentiality.
Version Control: Keep track of document revisions and history for auditing and rollback purposes.
Collaborative Editing: Allow multiple users to work on documents simultaneously, boosting teamwork and efficiency.
## Installation and Setup

***Ensure the following things are running***
- Redis Server at port 6379
- ElasticSearch at 9992
- Celery worker
- Postgres storage

Enter the credentials in **settings.py**

Then for running the backend:
`python manage.py runserver`
**NOTE**: Make the migrations first and ensure latest version of python and django using a virtual enviorment made by `python -m venv venv && source /venv/bin/activate` 

For running the Frontend:
`yarn && yarn run dev`
**NOTE**: Ensure latest version of node and yarn while running the above command




