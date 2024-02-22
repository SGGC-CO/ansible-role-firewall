# ansible-role-firewall

enable firewall and add rules to it.

## Requirements

none

## Variables

1. playbook.yml

```yaml
proxy_enable: "0 | 1"
```

2. inventory.ini

```yaml
sshport: "port number"
proxy_ip: "ip address of proxy server"
ssh_private_key_file: "path to private key file"
```

## Dependencies

none

## Example Playbook

`tests/test.yml`

`cd tests` and run the playbook with the following command:

```yaml
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory.ini test.yml --ask-become-pass
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
