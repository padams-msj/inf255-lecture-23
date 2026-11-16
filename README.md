# lecture-23

INF255 starter for Lecture 24: the Animal Shelter app, its Express server, and its SQLite database as they stood at the end of Lecture 23. Animals can be added, edited, toggled, and deleted, and every change is saved in the database.

```sh
npm install
node seed.js
```

Terminal 1, the API:

```sh
node --watch server.js
```

Terminal 2, the Vue app:

```sh
npm run dev
```

Run `node seed.js` again at any time to reset the database to the original 6 animals.
