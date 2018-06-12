# Role Name

[![Build Status](https://travis-ci.com/EGI-Foundation/ansible-role-caso.svg?branch=master)](https://travis-ci.com/EGI-Foundation/ansible-role-caso)

<!-- A brief description of the role goes here. -->

## Requirements

See the dependencies on `defaults/main.yml`

## Role Variables

Variables are described in `defaults/main.yml`.
Be sure to set at least a list of VOs to enable at your site.

The site name should correspond to the name of the site in GOC.

## Dependencies

<!--
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Use https://galaxy.ansible.com/EGI-Foundation/ roles first if possible.
-->

## Example Playbook

You should use this role with the [EGI-Foundation.cmd](https://galaxy.ansible.com/EGI-Foundation/cmd/) role
<!--
Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:
-->

```yaml
    - hosts: servers
      roles:
         - { role: EGI-Foundation.cmd}
         - { role: EGI-Foundation.caso, vos: ["ops","dteam"] }
```

## License

Apache-2.0

## Author Information

See AUTHORS.md
<!--
Add the relevant contributors
-->