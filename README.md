# ansible-use-before-define

Minimal playbook to demonstrate a surprising effect of default variables being
in scope before they are defined.

Simply run

```bash
ansible-playbook --connection=local -i localhost, use-before-define-of-globals.yml
```
