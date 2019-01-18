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

### Build the image
```
docker build -t schema-server .
```
### Run the container
```
docker run -p 8888:80 schema-server
```
