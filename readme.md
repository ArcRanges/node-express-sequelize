# node-express-sequelize
CRUD API compatible with Postgres or sqlite3
*Reference: https://sequelize.org/master/manual/getting-started.html*
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