# docker-gistie
Dockerized version of [Gistie] (https://github.com/gmarik/Gistie)

[Gistie] (https://github.com/gmarik/Gistie) is an open source Git-based pastebin implementation that enables sharing snippets(aka Gist) using simple web UI.
Every Gist is a *Git repository* thus **versioned** and **cloneable**. Heavily inspired by gist.github.com

#### Starting Docker Container:
```
$ docker run -d -p 3000:3000 nirmalpathak/docker-gistie
```
The above command will start gistie application on port 3000 of your docker host. You can go to http://localhost:3000 to use the applicaiton.
