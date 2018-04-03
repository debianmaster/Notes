```
yum install ansible
ansible all -m shell -a "date" -i hosts
ansible all -m shell -a "getenforce" -i hosts
ansible all -m shell -a "ping -c 1 master1" -i hosts
ansible all -m shell -a "yum repolist " -i hosts
```
https://docs.openshift.com/container-platform/3.9/install_config/install/prerequisites.html

