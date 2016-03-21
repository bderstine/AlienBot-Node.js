### ServerAdmin.io - AlienBot

## Quickstart

Tested on Ubuntu 14.04, node v0.12.7
* $ git clone https://github.com/bderstine/AlienBot-Node /srv/alienbot.com
* $ cd /srv/alienbot.com
* $ npm install
* $ mkdir log
* $ chmod +x init/node-alienbot.sh
* $ ln -s /etc/init.d/alienbot /srv/alienbot.com/init/node-alienbot.sh
* $ service alienbot start

## Test

* $ curl -X POST --data "user_name=foobar" http://localhost:3000/hello
* {"text":"Hello, foobar!"}

## Why?

I wanted to see what it took to build a Slack bot with Node.js.

Thanks for stopping by and visiting! 

-Brad

This is mostly a result of trying: http://www.sitepoint.com/getting-started-slack-bots/
