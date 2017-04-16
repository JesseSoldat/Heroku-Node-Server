nodemon server.js -e js,hbs

ssh -v git@heroku.com

env
heroku login
heroku create
git push heroku
heroku open