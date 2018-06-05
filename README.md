# project-tools

Set of tools inside Docker containers, using docker-compose.

### Current tools
- [x] git
  - [ ] gitlab
  - [x] gogs (https://gogs.io/)
  - [x] gitea (https://gitea.io)
- [x] kanboard (https://kanboard.org/)
- [x] mumble (murmur) (https://www.mumble.com/)
- [ ] collaborative pads
  - [ ] etherpad (http://etherpad.org/)
  - [ ] cryptopad
- [ ] nextcloud
- [x] dudle (https://github.com/kellerben/dudle/)
- [ ] chat
  - [ ] matrix
  - [ ] rocketchat
- [x] draw.io


Run with
```
docker-compose up
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
- draw
  - 4004
- gitea
  - 4005


In the directory /launcher there is a webapp with links to all the services.
