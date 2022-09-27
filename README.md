node-api
======================

### About

Source for a docker container for a node-red based API.

repo is synced with docker hub at brianapley/node-api.



## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name nodejs brianapley/node-api.
```

Once launched, UI can be accessed via http://host:1880/.

