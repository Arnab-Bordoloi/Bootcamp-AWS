# Run a sample application in Vanilla EC2

## Installing Jenkins & browse thru browser

- we create an EC2 instance by using Ubuntu OS and T2 micro. 
- We generate a new keypair to use. We also let the console create the SG.
- We have the key downloaded to a folder.
- We used ssh -i <key> <externalIP@ubuntu>.
- to switch user we `sudo su -`
- run below -
```
apt update
apt install openjdk-11-jdk
java --version
```
- then we install Jenkin from the commands
- then we try to browse by <ip:8080> but was unable to browse
- then we added a new security rule in security group to allow custom TCP at port 8080
- It worked !


