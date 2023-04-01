# ratchet-api
Websocket Using Ratchet PHP


# Documentation
## http://socketo.me/docs/hello-world

# How to run 
## Type to your command `php bin/server.php`

## Open your browser console and add this ff:
`var conn = new WebSocket('ws://localhost:8080');
conn.onopen = function(e) {
    console.log("Connection established!");
};

conn.onmessage = function(e) {
    console.log(e.data);
};`

## To send message command
`conn.send('Your message here')`
