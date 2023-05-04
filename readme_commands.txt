git init
heroku login
git add .
git commit -m "first commit"
git push heroku master
heroku ps:scale web=1  #free app!
heroku logs --tail #troubleshooting
heroku run app console #troubleshooting