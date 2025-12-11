# Role documentation for users

## Example user definiton in default/main.yml
```yml
- name: john
  password: "$6$rounds=656000$xyz..."
  groups:
    - web
    - databases
  admin_groups:
    - postgres
  hosts:
    - grafana
  admin_hosts:
    - vpn
```
