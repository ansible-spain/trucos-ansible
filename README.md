# trucos-ansible

## 1- Copiamos la clave de acceso del server para que no las pidas más
```linux
ssh-copy-id root@159.89.29.221
```

## 01 Ngix
```linux
ansible-playbook -i inventory.yml nginx.yml
ansible-playbook -i inventory.yml sync.yml
```
