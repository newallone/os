# os

# centos68

vagrant up --provider virtualbox

# fix authentication failure in vagrant

```bash
$ chmod 0700 /home/vagrant/.ssh
$ chmod 0600 /home/vagrant/.ssh/authorized_keys
$ chown -R vagrant /home/vagrant/.ssh
```
