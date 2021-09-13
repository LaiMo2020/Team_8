# more2offer

<p align="center">
  <img width="460" height="300" src="https://media.giphy.com/media/Q7q0KbMOijEUqOhAfr/giphy.gif?cid=ecf05e47si6bpufsc78iilfopi5siscy9ri7pxzy2lmu522s&rid=giphy.gif&ct=g">
  
 <br>
 Hello there, we are Access all Areas 👋
</p>
  

## more2offer
#### A person-centred recruitment hub that aims to increase inclusion in an ever-changing world. Users create a profile on the recruitment portal which includes all their basic data (name/contact etc) and fill in a questionnaire based on their specific needs. Users receive badges based on their specific needs - this avoids future awkwardness/conflict within the recruitment process and also later on in the workplace. Users also have the opportunity to showcase specific soft skills using badges.
The app URL is : 


## UX

### Goals 
This website is designed to encourage employers to think outside the box. Do you really want to miss out on an A-Grade employee just because they have a different ability set than what you have previously been used to? Because they didn't follow a traditional educational path?
The main aim of More2Offer is to support and encourage employers to educate and empower themselves, encouraging recruitment from a truly diverse pool of candidates, focusing on “Can Do” rather than “May Struggle With”.

### User stories
- As a job seeker with some additional/special needs (<-- not sure on terminology here), I want to be confident in applying somewhere, knowing the potential employer is open to employing people with additional needs. 
- As a job seeker, I want to have an opportunity to make employers aware of my specific needs and skills as early as possible.
- As a job seeker, I want to be able to save and edit my profile and application so that I can come back to it if I don’t want to finish it in one go, and be able to change my answers later. 

- As an employer, I want to attract a diverse workforce in order to access a diverse skill set.
- As an employer, I want to encourage people with disabilities to apply to our company.
- As an employer, I want to be informed early of how I can aid any applicants to give them the best opportunity to present themselves.
- As an employer, I want to learn more about both the benefits and challenges of employing people with additional needs.

#### Example User

Candidate "Pickle" has two disabilities. She is deaf and also has a stomach condition meaning she needs to stop working for 1 hour every 2 hours.
Pickle is a candidate who can offer a great deal to a company
Pickle is very open about her deafness and would like it to be known to a prospective employer so that :
The company can make reasonable adjustments to facilitate Pickle's working life
Pickle is proud of her achievements especially given her deafness and would like a badge on her profile stating signifying that she is deaf. Pickle likes this badge as it means she does not have to start her first conversation with the prospective employers outlining her deafness
However Pickle is less open about her second condition. She is willing to discuss her needs and loosely explain why but would really prefer not to talk about it at all.
Pickle has an additional badge on her profile stating that she does not work normal hours.
Pickle likes that the she is able to highlight her qualities and simplify her needs on her profile page helping ensure that the company that chooses her is indeed the right fit for her and she is for them.

A games company sees Pickle's profile and sees that she is deaf.
The company understands that Pickle's condition gives her a unique point of view in terms of developing games and would help others with a similar condition enjoy their games.
The company clicks also sees that Pickle requires an altered work schedule and is satisfied that this can be arranged.
The company likes the highlights and believes they match and so downloads CV

### Design
The site was specifically kept simple, with no visual noise or distracting images. This choice was made in order to design with accessability in mind, for the target audience. A simple but attractive font was chosen to add to the aesthetics. The blue colour for buttons and link text was chosen as it is an often-used colour within mental health circles, and aims to promote calm feelings.

#### Frontend
The site was specifically kept simple, with no visual noise or distracting images. This choice was made in order to design with accessability in mind, for the target audience. A simple but attractive font was chosen to add to the aesthetics. The blue colour for buttons and link text was chosen as it is an often-used colour within mental health circles, and aims to promote calm feelings.

#### Backend
There are two databases in MongoDB. One for users, and one for the questionnaire sections.
The Users database stores the information that has been entered from the Registration page. Once the questionnaire has been filled in, this then populates the badges array as well, with any relevant badges.

The second database is The Tabs database where there are the 5 sections/pages of the questionnaire. These are called when the user presses the 'next' button on each section.

### Wireframes
#### For the creation of the wireframes the Figma programme was used in order to be able to collaborate on the design. Throughout the development of the webpage the wireframes were very helpful for to reach the final design.

[Wireframes](docs/Wireframes.pdf)

## Features

### When the user is a job-seeker

#### Profile creation, Logging in and Out
The user can register their profile, using a username and password. Email and phone number are optional fields that are also stored.
The user can then log in and out.

#### Questionnaire
Once the user has a profile, they can then go through a questionnaire that will allocate them their badges. Each question with multiple tickboxes is displayed as its own page. The user can click on the 'Next' button to continue to the next question. 

#### Profile View
Once the questionnaire has been filled in, the logged in user will then see their profile, including the badges, on their home screen.

### When the user is the employer

#### Home/Profile

They can go to the 'profiles' page and view all of the profiles that have been created.

### Features Left to Implement

* Search/filter/sort on the view all profiles section

# Technologies Used


### 1. [HTML](https://html.com/)

For the basic structure of the project

### 2. [CSS](http://css.com/)

For the styling and design of the webpage

### 3. [JQuery ](https://jquery.com/) 

 Add dynamic and interactive elements to websites 

### 4.  [materialize](https://materializecss.com/)

Quick and responsive form and method to implement.

### 5. [GitHub](https://github.com/)

Platform to publish the webpage and interact with clients and the coder community

### 6. [Gitpod](https://www.gitpod.io/)

A coding editor with an adapted and easy coding environment

### 7. [GIT](https://git-scm.com/)

### 8. [Flask](https://flask.palletsprojects.com/en/1.1.x/)

A web framework  for Python
### 9. [Font Awesome](https://fontawesome.com/6?next=%2F)

As a resource of icons to style my page
### 10. [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
A web template engine for python 

### 11. [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

For live editing options while coding the page
### 12. [Figma](https://figma.com/)

To create wireframes
### 13. [Heroku](https://dashboard.heroku.com/apps)
Storing my app.
### 14. [Pyhton](https://www.python.org/)
Backend programmering language.
### 15. [MongoDB](https://www.mongodb.com/)
cross-platform document-oriented database/ NOSQL 

## Testing 

### Testing and review of the webpage

1. Tested devices:
  - Google Chrome
  - Safari
  - Iphone XR
  - MacBook Air

2. Tested browers
  - Google Chrome
  - Safari
  - iPad
  - iPhone SE

### Validation of the code/ Screenshoot 

- [vlaidator/screnshoot/Home-page-HTML]()
- [vlaidator/screnshoot/Questions-HTML]()
- [vlaidator/screnshoot/Login-HTML]()
- [vlaidator/screnshoot/Register-HTML])
- [vlaidator/screnshoot/Home-HTML]()
- [vlaidator/screnshoot/About-HTML]()


- [vlaidator/screnshoot/CSS]()
- [vlaidator/screnshoot/JS]()
- [vlaidator/screnshoot/PYTHON]()

### We have used the follwoing tech to test my code:
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
to visualise/edit my code live.
- [W3C/HTML](https://validator.w3.org/)
to check my  HTML code.

- [W3C/CSS](https://jigsaw.w3.org/css-validator/)
to check my CSS code.
- [Jshint](https://jshint.com/)
to check my JS code.
- [PEP8](http://pep8online.com/)
to check my python code

### Manual Testing:

To add after testing 


## Deployment

#### The project is stored in a Github [repository](https://github.com/LaiMo2020/more2offer)  & hosted on [Heroku]().

#### We have made the follwoing steps to deploye my app: 

### Github:

1. Creating a project repository Used the template of Code Institute to facilitate the environment of the editor
2. Clone the project to VScode.
3. Selected the Master branch GitHub pages section as a main branch
4. Created a dev-bracnhe to facilitate our collaboration without affecting the main branch.



### Heruko:


1- After creating an account at heroku and logged in, created a new application using the Heroku dashboard.

2- Creating a new databas collection in mongoDB. collect the mongodb URL after adding a username and password.

3- Go to settings tab in Heroku, click on 'reveal config vars' and add config vars such as IP (0.0.0.0), PORT (5000), MongoDB Name, MongoDB URI (URL with DB name and password that i have created).

4- Install Heroku in the terminal using 'npm install -g Heroku'.

5- Log into Heroku in the terminal using 'heroku login' and follow the on screen instructions to log in.

6- Creating env.py to store the festive data such as secret keys 

7- Create a requirements.txt in the terminal using 'pip3 freeze > requirements.txt'.

8- Create a Procfile in the terminal using 'echo web: python app.py > Procfile'.

9- Deploy the app to Heroku, adding the following: IP, MONGO_DBNAME, MONGO_URI, PORT, SECRET_KEY. [env.py]()

10- Connect GitHub to Heroku via the console using 'heroku git:remote a InhabitU.

11-Commit all files in my project in the terminal  using 'git add .' and 'git commit -m "comment"'.

12- Deploy the project to Heroku in the terminal using 'git push heroku master'.



### Running the application locally using VScode:


1- Install the necessary libraries specified in the requirements.txt.

2- Set environment variables by creating and adding them into a env .py file.

3- Create a .gitignore file in the root directory and add the env. py file to avoid it being pushed to GitHub. to protect sensitive data.

4- Import the env. py file into the app. py file. and, add the following: IP, MONGO_DBNAME, MONGO_URI, PORT, SECRET_KEY. [env.py](https://github.com/LaiMo2020/InhabitU/blob/master/static/deployment/env.py%20enviro.png)

5- Run the application, in the terminal : python3 app .py
