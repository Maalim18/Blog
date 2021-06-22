# Title
a Blog Website
## Author
mohamed Maalim Ali

# Description
it is a personal blogging website where you can create blogs  and other users can read and comment on them. 

# Features
you can  do the following

See all blogs
Create an account
Log in
Create a blog
Comment on a blog
See comments posted on each individual blog
Edit your profile i.e will be able to add a short bio about yourself and a profile picture
# Development
Getting started
Prerequisites
python3.8
virtual environment
pip
Cloning
In your terminal:

  $ git clone https://github.com/Maalim18/Blog.git
  $ cd blog-website
Running the Application
Install virtual environment using $ python3.8 -m venv env

Activate virtual environment using $ source env/bin/activate

Download pip in our environment using $ curl https://bootstrap.pypa.io/get-pip.py | python
Create a start.sh file in the root of the folder and add the following code:

  export MAIL_USERNAME=<your-email-address>
  export MAIL_PASSWORD=<your-email-password>
  export SECRET_KEY=<your-secret-key>
Edit the configuration instance in manage.py by commenting on production instance and uncommenting development instance

## To run the application, in your terminal:

  $ chmod a+x start.sh
  $ ./start.sh

# Technologies Used
Python3.8
Flask
HTML
Bootstrap







# License
MIT License












