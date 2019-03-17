# Heroku support for Learning Locker

To run Locally

1. Update `REDIS_URL` and `MONGO_URL`
2. run `./run-xapi.sh`

To run on heroku:

1. `heroku create`
2. `heroku stack:set container`
3. `git push heroku master`
