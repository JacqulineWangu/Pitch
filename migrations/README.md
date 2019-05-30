# PITCH-APP
## Author
**Jacquline Wangu**
## Description
This is an app that allows users to post pitches and comment on other people's pitches like or dislike. Pitch is an interactive app whereby users can share on their creative pitches.

## User stories

1. As a user, I would like to see the pitches other people have posted.
2. As a user, I would like to vote on the pitch they liked and give it a downvote or upvote.
3. As a user, I would like to be signed in for me to leave a comment.
4. As a user, I would like to receive a welcoming email once I sign up.
5. As a user, I would like to view the pitches I have created in my profile page.
6. As a user, I would like to comment on the different pitches and leave feedback.
7. As a user, I would like to submit a pitch in any category.
8. As a user, I would like to view the different categories.


## Project Setup/Instructions
Use the following commands to get to Pitch app with ease.
* git clone https://github.com/JacqulineWangu/Pitch.git
* install python 3.6
* install  Postgresql
* cd Pitch
* get to the virtual environment by using source virtual/bin/active
* Edit the start.sh file with your SECRET_KEY,MAIL_USERNAME & MAIL_PASSWORD
* Run chmod a+x start.sh
* for either code or atom navigate to ur prefered one
* Run ./start.sh. then ctrl+rightclick or alt+rightclick on the link that appears on ther terminal.

## BDD

|  BEHAVIOUR                                 | INPUT                                     |      OUTPUT                        |
|--------------------------------------------|-------------------------------------------|------------------------------------|
| Sign up                                    | user email,username,password              | welcome email                      |
| Login                                      | registered user application credentials   | Loged in                           |
| Post Pitch                                 | Your Pitch                                | post displayed on home page        |
| Update Post                                | Text                                      | Updated Post                       |
| Comment                                    | Text                                      | comment post                       |
| Like or Dislike                            | Click event                               | likes or dislikes a pitch          |

## Technology used 
1. HTML and CSS
2. Python3.6
3. Flask Framework
4. Postgres
5. Heroku
6. Git
7. Javascript

## Known bugs
Currently, there are no known bugs, if you encounter any get intouch with me at https://jacqulinewangu@gmail.com

## License
This software is Licensed under MIT License Copyright 2019 (Jacquline)