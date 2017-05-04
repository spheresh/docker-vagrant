# docker-vagrant

### Arguments
username - ex. vagrant
 
userpass - ex. vagrant


```
version: "2"
services:
  vagrant:
    build:
      context: .
      args:
        username: vagrant
        userpass: vagrant

```
