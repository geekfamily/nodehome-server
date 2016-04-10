# nodehome-server
Node home project - mosca docker container

#### DB install 
docker run -p 27017:27017 -v /data/db:/data/db cretzel/rpi-mongodb

#### Server Install
- pull code
```bash
sudo docker build -q -t nodehome/rpinodemosca .
```
```bash
docker run -p 1883:1883 -p 80:80 nodehome/rpinodemosca
```


