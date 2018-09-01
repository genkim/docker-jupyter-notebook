# jupyter-notebook

## Development

```
$ git clone

$ cd board/dev
$ vagrant up
```
When the virtual machine is up successfully, access to http://localhost:8080.

### About vboxsf error

```
local$ vagrant ssh
virtual$ sudo yum update -y kernel
virtual$ sudo yum install -y kernel-devel kernel-headers gcc gcc-c++
virtual$ exit
local$ vagrant reload --provision

```

## SSHing to web server.

```
local$ cd dev
local$ vagrant ssh
virtual$ docker exec -it jupyter /bin/bash
```

Source code is at /vagrant directory.
