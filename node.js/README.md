Realtime stats - Node.js, Socket.IO & Redis
===========================================

For complete walk-through, check my blog post on this: http://venublog.com/2013/06/26/realtime-web-stats-using-node-js-socket-io-and-redis/

Requirements:
-------------
- Node.js server (http://nodejs.org/)
    - Node.js modules
        - express (http://expressjs.com/)
        - redis (https://github.com/simplegeo/nodejs-redis)
        - socket.io (http://socket.io/#how-to-use)

- Redis server (http://redis.io/)

Get Started:
------------

- Clone the git repo and install dependency packages


```shell
    $ git clone git@github.com:vanuganti/realtime.git
    $ cd realtime
    $ cd node.js
    $ npm install
```

- Start the redis server (default localhost on port 6379)
- Start node with server.js

```shell
    $ node server.js
```

- Open client.html in browser code

```shell
    $ open client.html
```

- Publish a counter to 'realtime' channel in redis

```shell
    $ redis-cli publish realtime 99
```

- Notice the updated counter in browser

For additional details, check http://venublog.com/2013/06/26/realtime-web-stats-using-node-js-socket-io-and-redis/








