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
| AlmaLinux 10 | ✅ | [![AlmaLinux 10](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-10.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/almalinux-10.yml) |
| Fedora 42 | ✅ | [![Fedora 42](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-42.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-42.yml) |
| Fedora 43 | ✅ | [![Fedora 43](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-43.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-rpm_policy/actions/workflows/fedora-43.yml) |
| Ubuntu 22.04 | ❌ | N/A |
| Ubuntu 24.04 | ❌ | N/A |
| Ubuntu 26.04 | ❌ | N/A |
