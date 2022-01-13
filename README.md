# randomcomment

--- 
# Requirements

* Python (3.6, 3.7, 3.8, 3.9, 3.10)
* Django (2.2, 3.0, 3.1, 3.2, 4.0)

# Installation

Install using `pip`...

    pip install django

Cmd to your `manage.py` folder.

    pip install -r requirements.txt

After that we need migrate.

    python manage.py makemigrations   
# Run

For the runnig the server
    
    python manage.py runserver

Terminal:

    Watching for file changes with StatReloader
    Performing system checks...

    System check identified no issues (0 silenced).
    January 12, 2022 - 06:54:36
    Django version 3.1.2, using settings 'labexamraheel.settings'
    Starting development server at http://127.0.0.1:8000/
    Quit the server with CTRL-BREAK.

You can now open the API in your browser at `http://127.0.0.1:8000/`.

# working

![This is an image](IMG/Screenshot%20(3).png)

A image of a blog of the comment section

![This is an image](IMG/Screenshot%20(4).png)

A new comment section appears as a result of clicking the simple comment section in the blog.

To create a new comment we have to fill the details shown in the 'MAKE NEW COMMENT SECTION'.

After filling the deatils 'SUBMIT' should be invoked to create a new comment.

![This is an image](IMG/Screenshot%20(5).png)

After provoking the 'SUBMIT' button we could see the updation under the comment category.