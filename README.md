## Run a single Node.js script

```console
$ docker run -it --rm --name my-running-script -v "$PWD":/usr/src/app -w
/usr/src/app notegame/node-oracle:6 node your-daemon-or-script.js
```

## Original File

https://hub.docker.com/_/node/