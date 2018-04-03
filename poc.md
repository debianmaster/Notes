```
yum install ansible
ansible all -m shell -a "date" -i hosts
ansible all -m shell -a "getenforce" -i hosts
```
