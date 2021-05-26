# dockerDB
Automated database server setup.
Multiple container setup for different services to work together.
Dockerfile defines the webservice which will connect to database defined in docker-compose.yml. Latter will setup the two services and connect them to be able to use chinook database. 