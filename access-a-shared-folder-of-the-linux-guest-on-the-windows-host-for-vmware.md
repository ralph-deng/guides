# Access a shared folder of the Linux guest on the Windows host for VMware

##### 1) Edit the `/etc/fstab` and add this line
```bash
vmhgfs-fuse  /mnt/hgfs  fuse  defaults,allow_other  0  0
```
##### 2) Make this directory if it donesn't exist
```bash
sudo mkdir /mnt/hgfs
```
##### 3) Remount the shared folder
```bash
sudo mount -a
```
