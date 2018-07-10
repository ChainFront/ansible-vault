# ansible-vault
Ansible role for installing Hashicorp Vault.

This is very basic right now, and only configures a simple file 
storage backend. 

To test, use the Vagrantfile in the tests folder.

```$xslt
cd tests
vagrant up --provision
vagrant ssh
export VAULT_ADDR=http://127.0.0.1:8200
vault status
```
