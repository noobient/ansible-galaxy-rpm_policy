# bviktor.rpm_policy

## Synopsys

This role sets the RPM crypto policy.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `policy` | yes | `FUTURE` | Sets the RPM crypto policy. Allowed values are usually `DEFAULT`, `EMPTY`, `FIPS`, `FUTURE`, and `LEGACY`. |

## Examples

```yml
- include_role:
    name: bviktor.rpm_policy
  vars:
    policy: 'FUTURE'
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-rpm_policy/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-rpm_policy/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-rpm_policy/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-rpm_policy/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-rpm_policy/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-rpm_policy/actions/workflows/almalinux-9.yml) |
| Fedora 37 | ✅ | [![Fedora 37](https://github.com/noobient/ansible-rpm_policy/actions/workflows/fedora-37.yml/badge.svg)](https://github.com/noobient/ansible-rpm_policy/actions/workflows/fedora-37.yml) |
| Ubuntu 18.04 | ❌ | N/A |
| Ubuntu 20.04 | ❌ | N/A |
| Ubuntu 22.04 | ❌ | N/A |
