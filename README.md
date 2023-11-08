# noobient.rpm_policy

## Synopsys

This role sets the RPM crypto policy.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `policy` | yes | `FUTURE` | Sets the RPM crypto policy. Allowed values are usually `DEFAULT`, `EMPTY`, `FIPS`, `FUTURE`, and `LEGACY`. |

## Examples

```yml
- include_role:
    name: noobient.rpm_policy
  vars:
    policy: 'FUTURE'
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-9.yml) |
| Fedora 38 | ✅ | [![Fedora 38](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-38.yml) |
| Fedora 39 | ✅ | [![Fedora 39](https://github.com/noobient/ansible-galaxy-firewalld/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-firewalld/actions/workflows/fedora-39.yml) |
| Ubuntu 18.04 | ❌ | N/A |
| Ubuntu 20.04 | ❌ | N/A |
| Ubuntu 22.04 | ❌ | N/A |
