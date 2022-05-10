# Gentoo installer

## Download the requirements

```bash
ansible-galaxy install --force -r roles/requirements.yml
```

## How to use it?

```bash
ansible-playbook -u root -i <IP-OF-MACHINE>, main.yml -vv
```
