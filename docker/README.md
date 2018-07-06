# Docker boilerplate for an application using Nginx and PHP5.6

The docker-compose file will instantiate the following services:
* Mongo 3.4
* Mysql 5.6
* Nginx
* PHP5.6
* Redis
* Beanstalk
>**_Remember to close any process running on the following port of your local machine : 11300, 3306, 27017, 9000 and 8000!_**

#### Installation

Run `Docker-compose up` from the root directory

The root directory is bind mounted to the app container, so you can work from here.

Go to `localhost` in your browser to open the app.

**If your using any kind of framework, set the hosts of the services respectively**
* app host -> localhost
* mysql host -> mysql
* mongo host -> mongo
* redis host -> redis
* beanstalk host -> beanstalk






