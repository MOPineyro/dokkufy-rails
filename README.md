### Dokkufy vagrant server

Heroku mock-staging server using vagrant, docker, dokku, and dokkufy gem.

Install dokkufy:
```sh
$ gem install dokkufy
```

Install and provision vagrant machine:
```sh
$ vagrant up
```

Dokkufy vagrant server:
```sh
$ dokkufy server
```
current box ip address (see Vagrantfile): 192.168.51.4
Default vagrant user and pass: vagrant/vagrant

Clone repo and cd into directory:
```sh
$ git clone [repo]
$ cd [repo]
```

Dokkufy app:
```sh
$ dokkufy app
```
Server ip same as above. Leave other fields empty.

Push app to new staging server:
```sh
$ git push dokku master
```
Server ip same as above. Leave other fields empty.