# django-blog-website
This project is a Multi-User blog website which is create using Django 1.10.
Here an Authorized user can create, edit and publish the posts and the visitors can add comments to it.

## Prerequisites
Virtual environment(optional but recommended),pip

## Installing

To install Virtual Environment:
```
https://conda.io/docs/install/quick.html#quick-install
```
Then we can activate virtual environment and install files from requirements.txt in the command line terminal by using:
```
pip install -r requirements.txt
```

## Execution:

We now download the folders and files.

To login into the website or also to access admin page, firstly we need to create super user:
```
python manage.py createsuperuser
```
and now we enter the required fields to successfully create superuser.

Now we run the server and enter the superuser credentials in order to log into the website:
```
python manage.py runserver 
```

Then we go to browser and type the following url:
```
http://127.0.0.1:8000/
```

To access admin page, we go to browser and type the following url and type in the login credentials used to create superuser:

```
http://127.0.0.1:8000/admin/
```
After logging in, we can now create a post, save it as a draft, publish it or delete it and also visitors can comment on the posts.

# You can find the Demo Images in the ISSUES Section
