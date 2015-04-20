###Attention
- This image is work in progress. It will be changed.
- Root password is "root". Please change it.


###Start
```
$ docker run -d --name mysql -p 3306:3306 takeharu/ubuntu-mysql
```

###Connect from CLI
```
$ docker exec -it mysql /bin/bash
$ mysql -u root -proot
```

###Connect from container
```
$ docker run -d --name <container_name> --link mysql:db -P <image_name>
```


