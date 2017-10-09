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
(...)
dockercomposenetworkslow_hello_1 exited with code 0

real	0m16.756s
user	0m0.572s
sys	0m0.084s
```
