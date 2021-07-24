# 								Jobji_Nginx

**Jobji** - Django Framework project about job. The same project like this https://github.com/DenisB7/Jobji, deployed on Heroku using gunicorn + serving static files by Nginx.

Some information:
- you can sign up and sign in, account have a menu where you can create, change, add information about your company, vacancy and/or resume
- search information
- deployed on Heroku with gunicorn
- serving static files with Nginx

Questions about deploying on Heroku with Nginx:
1. Only one static image didn't appears here /vacancies/1/sent (it doesn't matter which uri you will set 1/2/3/4/5 the same problem appears), which in staticfiles folder, it isn't show up. 
2. Is it possible to use Nginx without gunicorn? 

I'm new in all this stuff, so didn't know is it efficient and worth it to puzzle over it? So, any help is appreciated.
