# how-to-nginx

### Create password file
First install relevant tools
```
apt -y install apache2-utils
```
Next create the file. Usually it has "hidden" name like `.htpasswd` (with dot) but I don't care here
```
htpasswd -c htpasswd USERNAME
```
Type password when prompted
