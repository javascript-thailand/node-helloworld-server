# nodejs-helloworld

[https://www.facebook.com/JavaScriptThailand/](https://www.facebook.com/JavaScriptThailand/)

Run the following commands one by one:

docker run --name node --rm --mount type=bind,source="$(pwd)"/js,target=/js -p 8888:8888 node:8 node /js/helloworld-server.js

curl 127.0.0.1:8888

docker rm -f node