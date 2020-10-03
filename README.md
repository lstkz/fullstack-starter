# fullstack-starter

## requirement
- node v12
- yarn
- mongodb



## deployment
```
yarn
# terminal 1
cd apps/api
yarn run dev

# terminal 2
cd app/front
yarn run dev
```


## configuration
Create `.env` in root.
Options:
- `MONGO_URL` - the mongo url
- `MONGO_DB_NAME` - the mongo database name
- `PORT` - (optional) the port to listen (default: 3000) 


## Heroku deployment
- Create a new heroku app, and link it to the github repository.
- Set env variables from the "configuration" section.
- App should be deployed automatically on every push to master.
- You can create a free mongodb database on https://cloud.mongodb.com/