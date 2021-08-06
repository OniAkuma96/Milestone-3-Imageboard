# R3view

R3view is a forum for discussion on anything, the emphasis is on free discussion by its users. Here registered users are free to make posts and reply to posts. 
Posts will have a title, body, and linked image while replies will just have a body and image (optional). 
Posts will also have some additional info such as who made the post, at what time, and on what day. Posts and replies are displayed newest first.
Registered users will be able to navigate to their profile page to see all the posts they have made.
This site is for registered users who want free and open discussion by making posts and replying to other posts and also for non-registered users who wish to read the posts.

## Features

### Existing Features

- __Navigation Bar__

    - The site will contain a few pages and users will be able to navigate through them at the top of the page.
    - Some navigation links will only be available to registered users.
    - Registered users can navigate to the profile page which has all their posts displayed.
    - Registered users also have the option to sign out.
    - Users that are not logged in will have the option to register or sign in if already registered.

- __Register and Login__

    - Users are free to register with a username and password. Registered users can login by providing their username and password.

- __Profile Page__

    - Registered users can navigate to the profile page to see all the posts they have made.

- __New Post Button__

    - Registered users are free to make new posts from the homepage.

- __View Replies Button__

    - Both registered and non-registered users are free to view replies to a certain post.
    - Clicking this button will go to a page with the post in question and all replies to said post indented below.

- __Reply Button__

    - Only registered users are allowed to make replies, which are then displayed.

- __Delete Post/Reply__

    - Users can delete posts/replies they have made.

- __Edit Post/Reply__

    - Users can edit a post/reply they have made.

### Features Left to Implement

- Like system

    - A system where registered users can 'like' a post or a reply, wont change how much the post or reply is seen as that is dictated by submission date/time.

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS](https://en.wikipedia.org/wiki/CSS)

- [Python](https://www.python.org/doc/)

- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
    - Micro web framework written in Python to build application

- [Heroku](https://dashboard.heroku.com/login)
    - For deployment of Python application

- [MongoDB](https://www.mongodb.com/)
    - As a database for storing infomation

- [jQuery](https://jquery.com/)

- [Materialize](https://materializecss.com/)
    - For a webpage framework

- [Font Awsome](https://fontawesome.com/)
    - For icons

## Testing

### Validator Testing

### Unfixed Bugs

## Deployment

- I deployed my app to Heroku after getting Flask running by doing the following:

1 Created requirements.txt file so Heroku knows what it needs to run app using pip3 freeze --local > requirements.txt command in terminal.

2 Created Procfile needed for Heroku to run app using echo web: python app.py > Procfile command in terminal.

3 Logged in to Heroku and clicked on 'create new app', set app name to r3view, and region to Europe.

4 On deploy tab clicked on Connect to GitHub button to setup automatic deployment. Searched for repo name and clicked connect.

5 Navigate to settings tab and reveal Config Vars and added keys and values.

6 Back in GitPod pushed requirements.txt and Procfile, enabled automatic deployment on Heroku, and clicked deploy branch. Heroku confirmed app was successfully deployed.

## Credits

### Content

### Media

### Code