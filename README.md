taskmanager
===========

Simple, Play-framework-based, task manager web app. Will serve as back-end for Android sample apps.

This app has:
- very basic CRUD functionality: webpage to manage tasks in the underlying database
- endpoints that return the tasks in the database as json

start server (locally)::

play -DapplyEvolutions.default=true run
or
play -DapplyEvolutions.default=true start


heroku::
http://dry-island-7582.herokuapp.com/