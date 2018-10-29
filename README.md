# t-pot-provisioning

Provisioning t-pot on scaleway server with [t-pot-autoinstall](https://github.com/dtag-dev-sec/t-pot-autoinstall) (T-Pot 17.10)

## Scaleway System Requirement
| Server Type | Memory | Storage | Image
|:-----------|:------------|:------------|:------------|
| START1-L | 8GB | 200GB | Ubuntu Xenial |

## Setup Local Machine
Install Ansible
```
# brew install ansible
```

Rewrite to the ip address of the server instance
```
# git clone git@github.com:kiyoto1022/tpot_provisioning.git
# cd tpot_provisioning
# vi hosts
```

## Start up the Remote computer
ssh connection possible

## Use
```
# ansible-playbook --private-key=~/.ssh/scaleway/id_rsa -u root -i hosts tpotservers.yml
```
