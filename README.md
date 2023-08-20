# Docker linux image from scratch

## Ubuntu base images

Ubuntu base image can be downloaded from here: http://cdimage.ubuntu.com/ubuntu-base/releases/

Choose an image and download the correct base .tar.gz file. For example

```
curl -L http://cdimage.ubuntu.com/ubuntu-base/releases/22.04/release/ubuntu-base-22.04-base-amd64.tar.gz -O
```

Then ADD the downloaded file in the Dockerfile (see Dockerfile.template in this directory).

## Alpine base images

The Alpine Linux base root file systems can be found in https://www.alpinelinux.org/downloads/

The example portrayed in Dockerfile.alpine.tamplate in this repository also installs bash, nodejs and npm.
