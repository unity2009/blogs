# blogs
#Here are the instructions to set up on your local machine:
#If you have install apache2 and mysql at your system. You need to stop apache2 and mysql using following command.
#Stop Local Apache and MySQL
$ sudo service apache2 stop
$ sudo service mysql stop

#Clone repository in your projects folder
$ git clone git@github.com:pras2309/somerset.git
$ cd somerset

Kill any running container if you have
$ docker stop $(docker ps -aq)

Open project folder in vscode and start making the theme

PHPMyAdmin URL:
http://localhost:8080/

Site URL:
http://somerset.com
