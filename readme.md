# node-express-sequelize
CRUD API compatible with Postgres or sqlite3

*References:*
- [Sequelize Docs](https://sequelize.org/master/manual/getting-started.html)
- [Youtube tutorial by Daving Tang](https://www.youtube.com/watch?v=VDgXAw7VynQ&feature=emb_logo&ab_channel=DavidTang)

## Optional Dependency
```
npm install -g nodemon
```
## Instructions
```
git clone <this repo>
cd node-express-sequelize
npm install
node app.js or nodemon app.js
# app should be running in localhost:8000
```

## Endpoints

```
[GET] - /api/tracks # lists all tracks available
[GET] - /api/playlists # lists all playlists available
[GET] - /api/albums # lists all albums available
[GET] - /api/tracks/:id # list a specific track
[GET] - /api/playlists/:id # list a specific playlist
[GET] - /api/albums/:id # list a specific album
[POST] - /api/artists/ # creates a new artist data
[DELETE] - /api/playlists/:id # deletes a specific playlist
```
