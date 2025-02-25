# ansible-role-passwordless-sudo #

[![GitHub Build Status](https://github.com/cisagov/ansible-role-passwordless-sudo/workflows/build/badge.svg)](https://github.com/cisagov/ansible-role-passwordless-sudo/actions)
[![CodeQL](https://github.com/cisagov/ansible-role-passwordless-sudo/workflows/CodeQL/badge.svg)](https://github.com/cisagov/ansible-role-passwordless-sudo/actions/workflows/codeql-analysis.yml)

This is a skeleton project that can be used to quickly get a new
[cisagov](https://github.com/cisagov) Ansible role GitHub project
started.  This skeleton project contains
[licensing information](LICENSE), as well as
[pre-commit hooks](https://pre-commit.com) and
[GitHub Actions](https://github.com/features/actions) configurations
appropriate for an Ansible role.

## Requirements ##

None.

## Role Variables ##

None.

<!--
| Variable | Description | Default | Required |
|----------|-------------|---------|----------|
| optional_variable | Describe its purpose. | `default_value` | No |
| required_variable | Describe its purpose. | n/a | Yes |
-->

## Dependencies ##

None.

## Installation ##

This role can be installed via the command:

```console
ansible-galaxy install --role-file path/to/requirements.yml
```

where `requirements.yml` looks like:

```yaml
---
- name: skeleton
  src: https://github.com/cisagov/ansible-role-passwordless-sudo
```

and may contain other roles as well.

For more information about installing Ansible roles via a YAML file,
please see [the `ansible-galaxy`
documentation](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html#installing-multiple-roles-from-a-file).

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: true
  become_method: sudo
  tasks:
    - name: Include skeleton
      ansible.builtin.include_role:
        name: skeleton
```

## New Repositories from a Skeleton ##

Please see our [Project Setup guide](https://github.com/cisagov/development-guide/tree/develop/project_setup)
for step-by-step instructions on how to start a new repository from
a skeleton. This will save you time and effort when configuring a
new repository!

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

## License ##

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

## Author Information ##

First Last - <first.last@gwe.cisa.dhs.gov>
