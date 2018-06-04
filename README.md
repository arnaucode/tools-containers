# project-tools

Set of tools inside Docker containers, using docker-compose.

### Current tools
- [x] gitlab / gogs (https://gogs.io/) / gitea (https://gitea.io)
- [x] kanboard (https://kanboard.org/)
- [x] mumble (murmur) (https://www.mumble.com/)
- [ ] etherpad (http://etherpad.org/) / cryptopad
- [ ] nextcloud
- [x] dudle (https://github.com/kellerben/dudle/)
- [ ] matrix/rocketchat
- [ ] draw.io


Run with
```
POSTGRES_USER=user1 POSTGRES_PASSWORD=user1 docker-compose up
```

Ports:
- launcher
  - 8080
- gogs
  - 4000
- kanboard
  - 4001
- etherpad
  - 4002
- dudle
  - 4003


In the directory /launcher there is a webapp with links to all the services.
