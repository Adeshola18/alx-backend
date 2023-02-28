#       0x02. i18n

In this project, we are interested in Learning how to parametrize Flask templates to display different languages, how to infer the correct locale based on URL parameters, user settings or request headers and how to localize timestamps.

## Tasks : pags_with_curl

* **0. Basic Flask app**
First you will setup a basic Flask app in 0-app.py. Create a single / route and an index.html template that simply outputs “Welcome to Holberton” as page title (<title>) and “Hello world” as header (<h1>).

* **1. Basic Babel setup**

Install the Babel Flask extension:

$ pip3 install flask_babel

Then instantiate the Babel object in your app. Store it in a module-level variable named babel.

In order to configure available languages in our app, you will create a Config class that has a LANGUAGES class attribute equal to ["en", "fr"].

Use Config to set Babel’s default locale ("en") and timezone ("UTC").

Use that class as config for your Flask app.

* 

Create a get_locale function with the babel.localeselector decorator. Use request.accept_languages to determine the best match with our supported languages.

* **3. Parametrize templates*









