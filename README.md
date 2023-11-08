# ApplianceHell

ApplianceHell Game. The totally pointless star collecting game.

## Play it now on itch

- https://takesthebiscuit.itch.io/appliance-hell 


## Credits/open source
- phaser https://phaser.io/ - opensource game engine in js [ A fast, free and fun open source framework for Canvas and WebGL powered browser games. ]
- github.com/takesthebiscuit - project author
- Inspiration: An ex-pat British guy called Rob who (once?) forgot to put the washing machine on

## Building

- npm i

## Running locally

- npm start
- visit http://127.0.0.1:8080 in a browser

## Coding

- modify index.html and refresh your browser (no hot module reload here)

## Publishing

- npm run release
- upload /dist/itchio.ziop to itch
- or, copy assets directory and index.html including node_modules to a webserver (phaser required)

## Playing

- use WASD to collect stars
- you can collect many stars at a time
- once you have collected all visible stars take them to the washing machine
- colliding with the washing machine is enough to drop the stars
- collect all stars in a 'round' and the washing machine will run
- once the washing machine finishes a cycle more stars spawn
- collect all stars in all rounds until you see 'YOU WIN'
- record your time, or don't

## Playtest feedback and future ideas

- more machines
- randomise the platform elements
- gravity/jump mechanism is a bit odd

## Issues

- see github issue tracker