# ADLab Week 2

## Intro
Last session we looked at areas such as basic app architecture and the WebApp Framework. Move on to explore the other topics of chapter 2 all of which will help you with your coursework. 
![Topic Overview for Lab 2](resources/ADLab2_Overview.png)

## Task

Continue reading through chapter 2 of the book Programming Google App Engine, then see if you can answer the following questions:

- How difficult is it to make resources available only after logging in?
I couldn't find anything in the chapter but I imagine it would be annoying for large scale applications to load resources at log in as there may be a ton of things happening on the app that may not load quickly unless preloaded before login 
- What is jinja2 and why is it a good idea to use such a thing?
Jinja2 is a templating system that is written in Python. It is a good idea to use a templating system as if you just write out templates in the app code it can get very messy and crowded as you are handling everything in script. Templates are stored in a seperate directory.
- Which Google services can be used to deal with users?
Users API
- What object makes app variables available to html templates?
Context
- How does the datastore identify records? 
By using the key that the record was created with
- Why would you use Memcache?
Memcache is a service provided by Google App Engine which allows data to be stored in memory. You would use this to store things like user session data etc. This is quicker than using the datastore.
- What facilities does the Google App Engine provide to help develop and monitor applications? 
Development Server Console, Python Console

# Further Reading for this Week

Read through Chapter 3 (Configuring an application).
