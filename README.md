# Foodbarrio ReactNative & GraphQL test

The goal is to implement a small Post/Comments app using GraphQL API and React Native.

## Screens
The app will have three screens.
 - [ ] **Login**  
 - [ ] **List of posts**  
 - [ ] **Create/Edit post**  
 - [ ] **Post details**

### Navigation
 - The user inserts his/her username in the "Login" screen to enter the app. If the inserted username doesn't exists, it will be created.
 - After the login the user is moved to the "List of posts" screen where he/she can scroll the list of available posts (each post indicating when it has been created, the number of comments and the number of likes received).
 - From the "List of posts" screen the user can navigate back to the "Login" screen (logout) or to the "Post details" screen by tapping on one post.
 - In the "Post details" screen the user can scroll the list of available comments (each comment indicating when it has been created and the number of likes received).
 - From the "Post details" screen the user can navigate back to the "Login" screen (logout) or to the "List of posts" screen.

## Use cases
### Must have
As a user I can
 - [ ] enter the app with a username
 - [ ] see all available posts
 - [ ] create new posts
 - [ ] edit/delete my posts
 - [ ] like and unlike my or other posts
 - [ ] create new comments on my or other posts
 - [ ] edit/delete my comments on posts
 - [ ] like and unlike my or other comments

As a user I can't
 - [ ] delete or edit posts of other users
 - [ ] delete or edit comments of other users
 
### Desiderable
As a user I can
 - [ ] see new posts from other users without refreshing the "List of posts" screen
 - [ ] see new comments from other users without refreshing the "Post Details" screen
 - [ ] see new likes from other users without refresing the "Post Details" 

### Nive to have
As a user I can
 - [ ] search content in the posts

## Data structure
This is only an example of a possible data structure that can be used
### User
 - [ ] username
 
### Posts
 - [ ] username of the author
 - [ ] title
 - [ ] content
 - [ ] createdAt

### Comments
 - [ ] parentPost
 - [ ] username of the author
 - [ ] title
 - [ ] content
 - [ ] createdAt
 
### Likes
 - [ ] parentPost or parentComment
 - [ ] username of the author
 - [ ] createdAt

## Tools that you have to use
### Must have
 - NodeJS and NPM
 - Apollo Server (GraphQL) 
 - Apollo Client
 - React Navigation

### Desiderable
 - Express
 - Knex (with migrations)
 - PostgreSQL

### Nice to have
 - Expo
 
## Documentation
All steps to install, maintain and run the app must be documented 

## NOTE
The submission will be **DISCARDED** if it **DOES NOT** provide instructions on how to install and configure the test environment (server, app, database,...).

## Submission

Fork this repository and send us a pull request.
