# docker-compose-mailserver

Deploy `tvial/docker-mailserver` with `docker-compose`.

## Configure

````
cp .env-sample .env
````

And configure accordingly. See https://github.com/tomav/docker-mailserver/wiki for full configuration details.

## Deployment

````
docker-compose up -d
````

## Set Up

Read the wiki (linked above) and use the provided `setup.sh` script to finish the setup process.
