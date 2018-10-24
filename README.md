# MySQL-Docker

Import the project and go in the good repository

Build an image called docker-mysql with the next instruction 

```docker build -t docker-mysql .```

Hence, run it on the port 3306 in the container and make the OS map on the port 6603

```docker run -p 6603:3306 docker-mysql```

Open MySQL workbench and test a connection on the port 6603. It will works
