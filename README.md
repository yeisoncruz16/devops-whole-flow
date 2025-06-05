# Ansible Repository

This repository contains Ansible playbooks and roles for managing infrastructure across different environments.

## Environments

- **development**: For local development and testing.
- **staging**: Pre-production environment for integration testing.
- **production**: Live environment for end users.

## Usage

Run a playbook for a specific environment:

```sh
ansible-playbook -i inventories/<environment>/hosts.aws_ec2.yml site.yml
```

Replace `<environment>` with `dev`, `prod`

## Requirements

- Ansible 2.9+
- Python 3.x

## Contributing

Feel free to open issues or submit pull requests for improvements.
