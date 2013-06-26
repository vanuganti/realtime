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

- Start redis server (default localhost on port 6379)
- Start node with server.js
    <code>node server.js</code>
- Open client.html in browser code
- Publish a counter to 'realtime' channel in redis
    <code>redis-cli publish realtime 99</code>
- Notice the updated counter in browser

For additional details, check http://venublog.com/2013/06/26/realtime-web-stats-using-node-js-socket-io-and-redis/








