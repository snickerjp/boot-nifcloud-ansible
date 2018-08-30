# boot-nifcloud-ansible

## first

```
ansible-galaxy install --roles-path ./roles nifcloud.nifcloud
cp -a ./roles/nifcloud.nifcloud/library/* library/.
ansible-playbook -i hosts provision.yml
```

## edit hosts

```
[nifcl_hosts]
xxx.xxx.xxx.xxx # 起動したサーバのGlobal ip address
yyy.yyy.yyy.yyy # 起動したサーバのGlobal ip address
```

## provision Nginx

```
ansible-playbook -i hosts nginx.yml
```
