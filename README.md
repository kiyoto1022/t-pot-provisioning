# tpot_provisioning
Provision tpot to scaleway

## Setup for Mac OS X
```
# brew install ansible
```

## Rewrite ip xx.xx.xx.xx
```
# git clone git@github.com:kiyoto1022/tpot_provisioning.git
# cd tpot_provisioning
# vi hosts
```

## Use
```
# ansible-playbook --private-key=~/.ssh/id_rsa -i hosts tpotservers.yml
```
