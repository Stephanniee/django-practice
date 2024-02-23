## Django 
In this app, I created a basic view to display a message and linked it to a specific URL. When you execute python3 manage.py runserver, Django initiates a server that awaits requests. Upon receiving a request, Django examines the URL to determine the appropriate content to display. Views are defined in Python files, typically named views.py, where they can range from showcasing simple text to managing interactions with a database.

#### The creation of this Django app involved
1. Initiating a project.
2. Establishing an app within the project.
3. Configuring views and their corresponding URLs.

### Depolement
I deployed the project by creating a Heroku app and attaching our GitHub repository to it. I specified the process type as web, indicating that Im running a web application. I opted to use Gunicorn to run the project because it is a more robust and scalable, production-ready server.

