Setup for my LXC containers.

Don't forget to bootstrap with:
```
$ ansible -i hosts -u ubuntu -k -K -s -m raw -a "apt-get install python python-apt python-pycurl sshpass -y" all
```
