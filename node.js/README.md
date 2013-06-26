Realtime stats - Node.js, Socket.IO & Redis
=================================================

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

- Start redis server (default localhost on port 6379)
- Start node with server.js
        node server.js
- Open client.html in browser code
- Publish a counter to 'realtime' channel in redis
        redis-cli publish realtime 99



