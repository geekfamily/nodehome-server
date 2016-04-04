# nodehome-server
Node home project - mosca docker container

#### Install
- pull code
```bash
sudo docker build -q -t nodehome/rpinodemosca .
```
```bash
docker run -p 1883:1883 -p 80:80 nodehome/rpinodemosca
```


