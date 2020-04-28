# tor-squid

Using squid and tor containers the utility gives an access the Internet thru proxy. To use the utility docker and docker-compose should be installed. Use the ofiicial docs to install: 
- https://docs.docker.com/engine/install/
- https://docs.docker.com/compose/install/. Also you can install docker-compose thru pip.

## How to run the docker containers
docker-compose  up -d

## Use proxy to access the Internet
Add the following http proxy to web-browser: localhost:3128

## Stop the docker containers
docker-compose down

## How to expand the exception list
1) Open the squid/acls/TOR.acl
2) Add the site to the list. Example: .site.com



