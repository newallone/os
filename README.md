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

# ref

https://github.com/CentOS/CentOS-Dockerfiles

https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

https://git-scm.com/book/ko/v1/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-Git-%EC%B5%9C%EC%B4%88-%EC%84%A4%EC%A0%95

https://git-scm.com/docs/git-config
