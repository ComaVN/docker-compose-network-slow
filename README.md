```
$ docker-compose down ; time docker-compose up
Removing dockercomposenetworkslow_hello_1 ... done
Removing network dockercomposenetworkslow_default
Creating network "dockercomposenetworkslow_default" with the default driver
```
(15 seconds pass here)
```
Creating dockercomposenetworkslow_hello_1
Attaching to dockercomposenetworkslow_hello_1
hello_1  | 
hello_1  | Hello from Docker!
hello_1  | This message shows that your installation appears to be working correctly.
hello_1  | 
hello_1  | To generate this message, Docker took the following steps:
hello_1  |  1. The Docker client contacted the Docker daemon.
hello_1  |  2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
hello_1  |  3. The Docker daemon created a new container from that image which runs the
hello_1  |     executable that produces the output you are currently reading.
hello_1  |  4. The Docker daemon streamed that output to the Docker client, which sent it
hello_1  |     to your terminal.
hello_1  | 
hello_1  | To try something more ambitious, you can run an Ubuntu container with:
hello_1  |  $ docker run -it ubuntu bash
hello_1  | 
hello_1  | Share images, automate workflows, and more with a free Docker ID:
hello_1  |  https://cloud.docker.com/
hello_1  | 
hello_1  | For more examples and ideas, visit:
hello_1  |  https://docs.docker.com/engine/userguide/
hello_1  | 
dockercomposenetworkslow_hello_1 exited with code 0

real	0m16.756s
user	0m0.572s
sys	0m0.084s
```
