
# Blog

Blog project is like other social media app project. It's 
basically a project about crud operation on relational database.

In this project an user can be created using registration ang logged
them in using login page. After login or authenticate an user can
create post. The post will be shown in the home page. Then te user 
can edit their post, update their post and also delete their post.
if the user is not authenticate user then they only can view post,
but will not able to access any functionality of any post.

User will aslo get the functionality to edit their porfile. And
they also able to view only their post created by them.

It's actually a common blog project like any other blog website.

## Installation

To install this-project, python version 3 and pip must nedeed.
After python3 Installation, need to install pipenv for 
creating virtual environment and then run the command of 'pipenv
install' to install all the dependencies for this project. 
That's all, that is all needed to install the project.

```bash
  cd blog
  pip install pipenv
  pipenv install
```    
## Run Locally

Clone the project

```bash
  git clone https://github.com/baloram-roy/blog-app.git
```

Go to the project directory

```bash
  cd blog
```

Install dependencies by installing pipenv. if pip not install in your system then install pip fisrt.

```bash
  pipenv install
```

Start the server

```bash
  python manage.py runserver
```

  