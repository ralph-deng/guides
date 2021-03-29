# Disable toolbar edge in full screen on the Windows host for VMware

##### 1) Search the `preferences.ini` which might be in the C:\Users\USERNAME\AppData\Roaming\VMware on host

##### 2) Edit the `preferences.ini` and add this line
```bash
pref.sharedFolder7.enabled = "TRUE"
```
##### 3) Restart the guest. Press `Ctrl` + `Alt` and then `Ctrl` + `Alt` + `Enter` on the guest if want to exit full screen 
