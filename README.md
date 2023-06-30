# Ansible Base

> Base configuration using ansible

## Features

- Installs common system packages (like `htop`, `ncdu` and `vim`)
- Hostname configuration
- Timezone configuration
- SSHD config hardening
- Upload ssh_keys to authorized_keys for `root`

## Getting started

```sh
ansible-galaxy install -r requirements.yml
```

## License

MIT