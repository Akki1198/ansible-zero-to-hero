Ansible vaults -

it is used to keep your sensitive data such as password. pass are the keys in encrypted files.
1.ansible-vault create filename.yml
2.ansible-vault edit file.yml
3.encrypt - password for previous playbook
4. decrypt - remove encryption

# Setup EC2 Collection and Authentication

## Install boto3

```
pip install boto3
```

## Install AWS Collection

```
ansible-galaxy collection install amazon.aws
```

## Setup Vault 

1. Create a password for vault

```
openssl rand -base64 2048 > vault.pass
```

2. Add your AWS credentials using the below vault command

```
ansible-vault create group_vars/all/pass.yml --vault-password-file vault.pass
```





