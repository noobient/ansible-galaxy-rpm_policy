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
| Fedora 40 | ✅ | [![Fedora 40](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-40.yml) |
| Fedora 41 | ✅ | [![Fedora 41](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-41.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-41.yml) |
| Ubuntu 20.04 | ❌ | N/A |
| Ubuntu 22.04 | ❌ | N/A |
| Ubuntu 24.04 | ❌ | N/A |
