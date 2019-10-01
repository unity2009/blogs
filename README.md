# blogs
#Here are the instructions to set up on your local machine:
#If you have install apache2 and mysql at your system. You need to stop apache2 and mysql using following command.
#Stop Local Apache and MySQL
````
$ sudo service apache2 stop
$ sudo service mysql stop
````
#Clone repository in your projects folder
````
$ git clone https://github.com/unity2009/blogs.git
$ cd blogs
#install docker at your local machine (Ubuntu).
````
````
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
$ sudo apt-get update
$ apt-cache policy docker-ce
$ sudo apt-get install -y docker-ce
$ sudo systemctl status docker
````
#Kill any running container if you have
````
$ docker stop $(docker ps -aq)
````
#You need to first build the configurations:
````
$ docker-compose up --build
````
#if not run, try using with sudo
#Open project folder in vscode and start making the theme

PHPMyAdmin URL:
http://localhost:8080/

Site URL:
http://yourname.com
