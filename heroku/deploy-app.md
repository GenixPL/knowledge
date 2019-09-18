1. `heroku create` [creates app in heroku]
2. add `Procfile` file to project's root folder with `web: node index.js` as its content, where `index.js` should be changed to app's starting file 
3. change port at which app listens (add `const PORT = process.env.PORT || 3003`, and change `app.listen(PORT,...)`)
4. `heroku addons:create cleardb:ignite` [adds ClearDB addon to project]
5. Change db connection parameters 
6. `git push heroku master` [pushes app to heroku]
7. `heroku ps:scale web=1`
8. `heroku open` [opens a website with app's url]

+ `heroku logs --tail` (`-t`) [shows logs]
+ `heroku config` [shows project's config]
  [`CLEARDB_DATABASE_URL: mysql://b68e2064709296:c7cb2362@us-cdbr-iron-east-02.cleardb.net/heroku_35e9a9a60bbfe9c?reconnect=true` 'b68e2064709296' - user, 'c7cb2362' - password, 'us-cdbr-iron-east-02.cleardb.net' - host, 'heroku_35e9a9a60bbfe9c' - database]