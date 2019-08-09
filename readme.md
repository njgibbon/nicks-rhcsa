# nicks-rhcsa
RHCSA stuff

# RHCSA
https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam

## RHEL7 VirtualBox on Mac Install notes
https://medium.com/pareture/rhel-7-on-virtualbox-on-mac-444ea866b116

## Docker Basics & Dockerised RHEL8 blog
https://medium.com/pareture/rhel-7-on-virtualbox-on-mac-444ea866b116

## Docker

### Pull RHEL8 Image
```
docker pull registry.access.redhat.com/ubi8/ubi:latest
```

#### Run RHEL8-Python3 Container Example
```
cd docker/rhel8-python3
docker build -t rhel8-python3 .
docker run -v ~/<path-to-this-repo>/docker/rhel8-python3/mount:/mount -it --rm rhel8-python3
```





