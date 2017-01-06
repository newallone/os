# os

# centos68

vagrant init bento/centos-6.8; vagrant up --provider virtualbox

or 

vagrant up --provider virtualbox

# fix authentication failure in vagrant

```bash
$ ls -larth /home/vagrant/ | grep .ssh
$ ls -larth /home/vagrant/.ssh

$ chmod 0700 /home/vagrant/.ssh
$ chmod 0600 /home/vagrant/.ssh/authorized_keys
$ chown -R vagrant /home/vagrant/.ssh
```
