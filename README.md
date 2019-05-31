# Gauge Taiko Docker

This is sample gauge project illustrating gauge + taiko usage in a docker container

## Prereuisite

* docker

## How to run
* Clone the repo
* Build image
    * Run `docker build . -t gauge-taiko`
* Run tests
    * Run `docker container run gauge-taiko npm test`

    or to run `gauge` args 

    * Run `docke container run gauge-taiko npm run gauge -- {args for gauge command}`