Love Letter
===========

You can use this repository to get a complete working version of the game
using Docker containers.

To fetch this repository and all submodules, just use the following command:
`git clone --recursive https://github.com/ludovicm67/love-letter.git`

Then go to the new directory with `cd love-letter` and run:
`docker-compose stop && docker-compose build && docker-compose rm -vf && docker-compose up`
to stop, build, remove old volumes, and run all required containers for the app.
