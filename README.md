# USAGE

## setup

```
curl -O https://raw.githubusercontent.com/zizochan/mac_ansible/master/setting.sh
chmod 755 ./setting.sh
sh ./setting.sh
```

## install

```
ansible-playbook -i inventory/localhost localhost.yml
ansible-playbook -i inventory/localhost localhost.yml --tags tag_name
```

