## create-react-app-with-heroku

### やったこと
```
$ npx create-react-app --template typescript create-react-app-with-heroku
$ brew tap heroku/brew && brew install heroku
$ heroku login
$ cd create-react-app-with-heroku/
$ git remote add origin git@github.com:KoinoEngineering/create-react-app-with-heroku.git
$ git push -u origin master
$ heroku create create-react-app-with-heroku -b https://github.com/mars/create-react-app-buildpack.git
$ git push heroku master
$ heroku open
```
