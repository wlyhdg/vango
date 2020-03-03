# vango
A project where I integrate Vue with Django

If you would like to create this project from scratch:
<br />Please check the <b>vango_instructions_steps.pdf</b> in the top repo for step by steps. Aight, I need to catch some ZzZ now.

Startup:

1. Clone the repo or manually download. You can clone by opening a console and typing

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>git clone https://github.com/wlyhdg/vango.git</code>

2. Go into main project directory

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>cd vango</code>

3. Use npm to install node.js module dependencies 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>npm install</code>

4. On the side, open another console and navigate to this same location. Then run

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>npm run dev</code>

&nbsp;&nbsp;&nbsp;&nbsp;We are done setting up this second console.

5. In the starting console, go into the directory that contains the python server running file 'manage.py'

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>cd vango/vango</code>

6. Run the server 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<code>python manage.py runserver</code>

Now you can go into vango/vango/frontend/src and this will act as your Vue main directory. Vue code is already working and you can add a components folder, Vuex, Vue Router, etc.

Django rest framework is also installed if you want to add APIs and test a full stack application.
