# tpot_provisioning
Provision tpot to scaleway

## Requirement
Setup for Mac OS X
```
# brew install ansible
```

## Rewrite ip xx.xx.xx.xx
Rewrite to the ip address of the server instance
```
# git clone git@github.com:kiyoto1022/tpot_provisioning.git
# cd tpot_provisioning
# vi hosts
```

## Use
Run provisioning....
```
# ansible-playbook --private-key=~/.ssh/id_rsa -i hosts tpotservers.yml
```
