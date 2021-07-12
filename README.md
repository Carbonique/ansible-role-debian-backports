- [About](#about)
- [Variables](#variables)

# About

This role adds Debian/Ubuntu backports and install apt packages from backports. This role is a stripped down and adjusted version of [ansible-role-debian-backports](https://github.com/jnv/ansible-role-debian-backports)

# Variables

For defaults see `defaults/main.yml`.

| Variable           | Description                                                                                                    | Default                  | Optional/Required |   |
|--------------------|----------------------------------------------------------------------------------------------------------------|--------------------------|-------------------|---|
| backport_packages    | List of packages to install from backports                                | null                     |              Optional |
