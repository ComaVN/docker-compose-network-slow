With defined subnet:
```
networks:
  default:
    ipam:
      config:
        - subnet: 172.17.0.0/28
```
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

real	0m16.647s
user	0m0.600s
sys	0m0.048s
```

Without defined subnet:
```
networks:
  default:
```
```
$ docker-compose down ; time docker-compose up
Removing dockercomposenetworkslow_hello_1 ... done
Removing network dockercomposenetworkslow_default
Creating network "dockercomposenetworkslow_default" with the default driver
Creating dockercomposenetworkslow_hello_1
Attaching to dockercomposenetworkslow_hello_1
hello_1  | 
hello_1  | Hello from Docker!
hello_1  | This message shows that your installation appears to be working correctly.
(...)
dockercomposenetworkslow_hello_1 exited with code 0

real	0m1.647s
user	0m0.584s
sys	0m0.056s
```
