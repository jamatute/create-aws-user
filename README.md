# create-aws-user

Create/Update AWS users

## Requirements

Boto installed

## Role Variables

* `temp_password`: Set up a temporary password
* `iam`: Dictionary with information of the IAM
  * `users`: List of users

## Dependencies

None

## Example playbook

```yaml
- hosts: all
  roles:
    - create-aws-user
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
