# Ansible Configuration

## Install Ansible

```bash
pip install ansible
```

## Run Ansible

```bash
ansible-playbook -i hosts playbook.yml
```

## Run Ansible with Vault

```bash
ansible-playbook -i inventory.ini playbook.yaml.ansible --ask-become-pass
```
