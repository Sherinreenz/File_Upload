# File_Upload
Upload, Update and Delete Files using Django Python
1. As a user, I can login to the platform using email address and password.
2. I will be able to see a list of all the files that I have uploaded. Not visible to external parties.
3. I can delete an already uploaded file, upload a new file while specifying some additional info such as a title, content, etc.
4. Also, I can share one of my files publicly using a URL generated.
# Backend Assesment using django - python

# Prerequisites
1. python > 3.8
2. pip 22.0.3
3. pipenv (if not available run the command pip install pipenv)
4. VS Code

## Setting up and Running the Assesment
1. Download and open the folder
2. Open powershell inside the folder location (ex: PS C:\Users\alija\OneDrive\Desktop\File_Upload-main>)
3. Run the following commands
   3.1. pipenv shell 
   3.2. pipenv install django
   3.3. pipenv install django-crispy-forms
   3.4. python manage.py makemigrations
   3.5. python manage.py migrate
   3.6. python manage.py runserver
4. Open  http://127.0.0.1:8000/ in a browser
