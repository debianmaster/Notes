```
yum install ansible
ansible all -m shell -a "date" -i hosts
ansible all -m shell -a "getenforce" -i hosts
ansible all -m shell -a "ping -c 1 master1" -i hosts
```

```
https://docs.openshift.org/latest/install_config/install/prerequisites.html
```
