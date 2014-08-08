# Deploying our blog to Heroku
Today we were basically following [this tutorial](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
First we reviewed the Heroku intro deck slides: https://files.gitter.im/codefellows/sea-b20-javascript/s75S/cf_heroku.pdf

```
 cd blog-test
 grunt --help
 which heroku
 brew search heroku
 heroku help
 vim Gruntfile.js
 cd ../blog-test
 grunt build   # DON'T forget this step!
 tree -L 2
 heroku login
 ls ~/.ssh     # Here we talked about ssh keys
 heroku help ps
 heroku help
 ls package.json
 npm install express --save
 git diff package.json
 git init
 git commit -m 'generated a site with yo browserify'
 cat .gitignore
 vim server.js # here we created a simple express static server
 # we also talked about environmental variables and process.env.PORT
 env
 node
 node server.js
 PORT=3000 node server.js
 node server
 git add .
 git commit -m 'add server and dist'
 git status
 tree dist
 heroku help create
 heroku create ivan-node-blog-42
 git remote -v
 git add Procfile
 git commit -m 'add Procfile for heroku'
 npm install -g foreman
 which nf
 nf --help
 nf start
 git push heroku master
 open http://ivan-node-blog-42.herokuapp.com   # in your browser
```

At the end of class we talked about the benefits of Pair Programming: http://c2.com/cgi/wiki?PairProgrammingBenefits
