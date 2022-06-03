# swserver

a web server exposing static files from a specified folder

with Docker, just:

```sh
docker run --publish 8000:8000 -v localfolder:/www swserver 
```