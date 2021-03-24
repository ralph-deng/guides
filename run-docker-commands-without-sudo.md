# Run Docker commands without sudo

##### 1) Add the `docker` group
```bash
sudo groupadd docker
```
##### 2) Add the user to the `docker` group
```bash
sudo adduser USERNAME docker
```
##### 3) Restart Docker service
```bash
sudo systemctl restart docker
```
##### 4) Logout and login again
