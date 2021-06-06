# 								Jobji_Nginx

**Jobji** - Django Framework project about job. The same project like this https://github.com/DenisB7/Jobji, but trying to deploy it using gunicorn + Nginx on Heroku.

Some information:
- you can sign up and sign in, account have a menu where you can create, change, add information about your company, vacancy and/or resume
- search information
- deployed on Heroku with gunicorn
- serving static files trying to do with Nginx

**Problems:**
1. I have only one static image, it isn't show up.
2. I want to serve media files also, but can't get it how to do it, if it possible, when you are using web developer mode in your browser it showing that media files served by Nginx (not Gunicorn), so i think it isn't work properly, because it isn't cached.

I'm new in all this stuff, so didn't know is it efficient and worth it to puzzle over it? So, any help is appreciated.