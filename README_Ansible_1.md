# Ansible Homework

## Environment
- Ubuntu VM (control node)
- Docker containers: centos7, ubuntu
- Ansible 2.16

## Inventory groups
- el → centos7
- deb → ubuntu
- local → localhost

## Results

- centos7 → CentOS → some_fact = el
- ubuntu → Ubuntu → some_fact = deb
- localhost → Ubuntu → some_fact = all default fact

## Vault
group_vars/deb and group_vars/el encrypted using ansible-vault (password: netology)

## Notes
- Fixed Docker connection issues
- Fixed disk space issue
- Fixed YAML inventory structure
