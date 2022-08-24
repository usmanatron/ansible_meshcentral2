# Ansible Role: template

A brief description of the role goes here.

## Requirements

This role assumes the following:

* TODO

## Role Variables

### Main Variables

| Name | Details |
| --- | --- |
|`meshcentral2_digest` | Docker digest to use. Typically starts with `SHA256:`.  (tags are not available for our chosen container). Get this from [here](https://hub.docker.com/r/technoexpress/meshcentral2)  |
|`meshcentral2_encryption_key` | NeDB Encryption Key |
| `meshcentral2_smtp_host` | Email host to use |
| `meshcentral2_smtp_port` | Post of the above Email host to use |
| `meshcentral2_smtp_from` | From address |
| `meshcentral2_smtp_username` | SMTP Authentication username |
| `meshcentral2_smtp_password` | SMTP Authentication password (Note: stored in plaintext in the config) |

### Default Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `app_name` | `traccar` | Used to name things |
| `app_folder` | `/apps/traccar` | The base directory for deployment |

## Dependencies

None

## License

MIT
