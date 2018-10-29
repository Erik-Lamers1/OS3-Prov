# OS3-Prov
Provisioning code for OS3. \
These ansible playbooks can be used to provision a new OS3 server after a reinstall.

### Installation
#### Client
```
apt-get install python-pip
pip install ansible
```

#### Server
```
apt-get install python
```

### Running
```
ansible-playbook --key-file ~/.ssh/<private-key> -i inventory/production ansible/configure_base.yml
```
