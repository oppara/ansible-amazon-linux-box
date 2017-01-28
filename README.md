# Try Ansible with AmazonLinux box

* timezone
* php
* composer
* wp-cli
* httpd

```
% ansible-playbook -i hosts setup.yml 
```

```
% vagrant init spscommerce/amazonlinux; vagrant up --provider virtualbox

% ssh -l vagrant 127.0.0.1 -p 2222 -i /path/to/vagrant_private_key

% ansible all -i hosts -m ping 
```
