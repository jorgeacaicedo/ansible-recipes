# Ansible configuration

Create `.ansible.cfg` file in your home:

| .ansible.cfg |
| :----------: |
```
[defaults]
inventory      = /home/user/.ansible/conf/hosts
```

Clone this repository in `.ansible` directory in your home:

```
mkdir ~/.ansible
cd ~/.ansible
git clone git@10.170.0.236:it/ansible.git
```

Rename the the repository directory to conf:

```
mv ansible conf
```