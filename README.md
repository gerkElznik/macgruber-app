# macgruber-app
A sample web app that serves up a picture of MacGruber.

## Test locally
```console
docker build -t macgruber-app:latest .
docker run -it --rm -p 8080:80 macgruber-app
```

### Open browser
http://localhost:8080