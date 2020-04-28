# tor-squid

The utility creates the proxy to access the Internet. To use the utility docker-compose should be installed. Use the ofiicial docs to install docker-compose: https://docs.docker.com/compose/install/. Also you can install docker-compose thru pip.

## How to run the docker containers
docker-compose  up -d

## Stop the docker containers
docker-compose down

## How to expand the exception list
1) Open the squid/acls/TOR.acl
2) Add the site to the list. Example: .site.com

