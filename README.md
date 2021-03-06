# Learning about Containers
This repo is to learn how Linux containers work under-the-hood

## Demo
[![asciicast](https://asciinema.org/a/WCoReYjM6pFJPCoqRtVEVo8eq.svg)](https://asciinema.org/a/WCoReYjM6pFJPCoqRtVEVo8eq)

## Pre-requisites
Install Valgrind
```
sudo apt-get install -y valgrind
```
## Build
```
mkdir build && cd build
cmake ..
make
```

## Run
Use Vagrant to set up a VM

```
vagrant up
vagrant ssh
sudo -i
cd /vagrant/build/
```


## Use Valgrind:
```
valgrind ./container run
```
