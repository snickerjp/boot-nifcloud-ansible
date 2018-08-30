# boot-nifcloud-ansible

## first

```
ansible-galaxy install --roles-path ./roles nifcloud.nifcloud
cp -a ./roles/nifcloud.nifcloud/library/* library/.
ansible-playbook -i hosts provision.yml
```
