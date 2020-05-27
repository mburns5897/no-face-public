# no-face-public
Public Access to ReadMe / no face api

# **No Face**

## Truly Anonymous and Democratic Social Network

## Goals

- **Anonymity:** Either achieved by not having a profile, or obscuring identity to server

- **Democracy:** Undesirable content is removed by democratic decision of users

- **Originality:** Original Content is ensured by only allowing content matching criteria.  Criteria could entail ML or be as simple as direct comparison to DB data

## Technologies

- **React:** Provides a front end UI

- **Django:** Controls REST Server and DB

  - Dependencies handled via pipenv

## Development

- **Changing DB:** Edit the models.py file to change DB info, after making changes run `pipenv run python manage.py makemigrations` then `pipenv run python manage.py migrate`.  If a new model is created, run `pipenv run python manage.py makemigrations <MODELNAME> <MODELNAME>` and `pipenv run python manage.py migrate <MODELNAME> <MODELNAME>`

- **Emptying DB:** Run `pipenv run python manage.py makemigrations --empty <MODELNAME> <MODELNAME>` then `pipenv run python manage.py migrate`

- **Accessing DB Via REST** The DB is accessed thru views.py

- **Running the Rest Server** Run `pipenv run  python manage.py runserver`.  the api/posts endpoint returns all Posts model objects.

- **React Dev** Following create-react-app conventions using webpack.  To Run react server, run `npm start` from no_face_web directory

## Questions 

1. What is the defining change in software that beats the incumbents (Reddit, Youtube, Twitter, IG, FB, TikTok) 
2. After the anonymity piece is lifted (ex: 1000 Likes), what is the differentiator from reddit, youtube etc?  
3. What's preventing someone from cheating the game if you don't need an account to upvote/downvote couldn't you just open like 100 tabs? 
4. If it is completely anon, then probably gonna see alot of hate speech etc etc., whats the plan to prevent this? (YikYak had this issue and it fucked them) 
5. What is the main goal? Is it to get out of anon and become a content creator? What's the catch for a user to leave incumbents? 



If there is a subreddit for a topic, there is a vertical social network opportunity.  
