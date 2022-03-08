# Ansible Collection: serdigital64.automation

## About

Ansible Roles for managing automation tools provisioning.

This collection is part of the [A:Platform64](https://github.com/serdigital64/aplatform64) project for automated infrastructure-as-code management.

## Content

| role                                                                                            | purpose                                           |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| [auto_aplatform64](https://aplatform64.readthedocs.io/en/latest/roles/auto_aplatform64)         | Automate the management of computing environments |
| [auto_ansible_control](https://aplatform64.readthedocs.io/en/latest/roles/auto_ansible_control) | Automate the management of Ansible Control Node   |
| [auto_ansible_node](https://aplatform64.readthedocs.io/en/latest/roles/auto_ansible_node)       | Automate the management of Ansible Managed Nodes  |

## Deployment

### Dependencies

- Ansible Collections:
  - ansible.posix
  - serdigital64.backup
  - serdigital64.system
  - serdigital64.security

### Installation Procedure

Manually install Ansible Collections from the Ansible Galaxy repository:

```shell
ansible-galaxy collection install --upgrade serdigital64.automation
```

Automatic installation is also available by deploying [A:Platform64](https://aplatform64.readthedocs.io/en/latest/#deployment)

## Contributing

Help on implementing new features and maintaining the code base is welcomed.

Please see the [guidelines](https://aplatform64.readthedocs.io/en/latest/contributing/guidelines) for further details.

## Author

- [SerDigital64](https://serdigital64.github.io/)

## License

[GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.txt)