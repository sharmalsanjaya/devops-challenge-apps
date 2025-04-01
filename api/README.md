# Devops API Appxx

fdffff
### install the node packages in the web container:dxdcd
```sh
→ docker-compose run api npm install
```
> Docker will download all necessary images for the container.

### start up the app:
```sh
→ docker-compose up
```

###  NOTE this app uses two env variables:

- PORT: the listening PORT
- DB: the postgresql url to connect

These two variables need to be set with docker-compose (API_PORT, API_DB).
