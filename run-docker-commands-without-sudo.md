# Run Docker commands without sudo

##### 1) Add the `docker` group
```console
sudo groupadd docker
```
##### 2) Add the user to the `docker` group
```console
sudo adduser [my-user-name] docker
```
##### 3) Restart Docker service
```console
sudo systemctl restart docker
```
##### 4) Logout and login again
