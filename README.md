# Role Name

Role to install and setup nfs-client

## Requirements

The client expects a nfs server to be available. If you don't want to be sock in the boot process, use the `nobootwait` option.

## Role Variables


## Dependencies


## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: nfs-clients
      roles:
         - { role: AdrianGPrado.nfs-client }

## License

BSD

## Author Information
------------------

[Adrian G Prado](https://github.com/AdrianGPrado)
