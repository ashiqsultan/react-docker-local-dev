# React local development in docker container with hot reloading
This is a demo app to facilitate React app development in docker container with hot reloading

> **Important**: Remember to rebuild Docker image if you make changes to the package.json file, as new dependencies won't be automatically installed in the container.


To start development run
`docker-compose up --build`

Once built next time simply run 
`docker-compose up`

**Files which makes this work**
- dockerfile
- docker-compose.yml
- vite.config.js
