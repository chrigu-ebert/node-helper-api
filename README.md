# Node Helper Api

## Setup

`git clone git@github.com:chrigu-ebert/node-helper-api.git .`
`cd node-helper-api/`
`npm install`

## Run debug mode

`DEBUG=express:* node ./bin/www`

NOTE: doesn't work with fish-shell.

## Run on server

### Using forever

`npm install forever -g`
`forever start bin/www`
