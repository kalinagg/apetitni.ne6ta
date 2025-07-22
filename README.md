How to restore database:
Copy <MONGO_URI> from Vercel env variables!
mongorestore --uri="<MONGO_URI>" Downloads/recipes.bson


How to backup database in bson archive format:
mongodump --uri="<MONGO_URI>" --archive=dump-archive


How to export database to json format:
mongoexport --uri="<MONGO_URI>" --collection recipes --out=recipes-2025.json --pretty