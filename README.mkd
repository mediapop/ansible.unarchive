# README.md
# Ansible Role: Unarchive

Make sure [unarchive](https://docs.ansible.com/ansible/unarchive_module.html) works in my roles.

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: mediapop.unarchive
```
        
## Example as a dependency in your meta


```yml
---
dependencies:
- role: mediapop.unarchive
```

## License

MIT
