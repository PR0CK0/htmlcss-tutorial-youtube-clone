https://htmlcss-tutorial-youtube-clone.herokuapp.com/

Steps for deploying a basic HTML app to Heroku...

* Needs a "buildpack"... HTML is not detected, so rename your index.html to index.php and it should work fine
* Assuming you have SSH keys from the keygen function in your C:/.ssh/
* Make your app
* Make a repo on Github Web
* Go to CLI in the local folder with your files
* git remote add origin [url given in Github web]
* git branch -M main
* git add .
* git commit -am "initial commit"
* git push -u origin main
* heroku login
* heroku create [app] OR heroku apps:open [appname, can get list by typing heroku apps]
* heroku git:remote -a [app name]
* git push heroku main