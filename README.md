# tpot_provisioning

Provision T-Pot to scaleway

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
Run provisioning....
```
# ansible-playbook --private-key=~/.ssh/scaleway/id_rsa -u root -i hosts tpotservers.yml
```
