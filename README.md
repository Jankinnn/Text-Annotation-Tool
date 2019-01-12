# Text-Annotation-Tool
<br>
A simple text annotation tool based on Django for producing custom datasets for Named Entity Recognition and other NLP tasks. This tool was developed to primarily help me tag SEC filings to observe how mutual funds leverage credit derivatives. <br>

`https://github.com/sudhamstarun/Understanding-Financial-Reports-using-Natural-Language-Processing`
<br>

## Requirements

1. Google Chrome or Chromium based browser
2. Python 3.6+
3. Django 2.0+ 


## Installation 
<br>
Clone the repository using the following set of commands:

`git clone https://github.com/sudhamstarun/Text-Annotation-Tool.git`

Now migrate the project by using:

`python3 manage.py migrate`

Finally, now create a user with the command:

`python3 manage.py createsuperuser`

Enter the usernme and email ID.


Now, run:

`python3 manage.py runserver`

and continue to the login page at `http://127.0.0.1:8000` to get started
