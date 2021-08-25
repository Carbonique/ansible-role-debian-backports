- [About](#about)
- [Installation](#installation)
- [Defaults & Variables](#defaults--variables)

# About

This role adds Debian/Ubuntu backports and install apt packages from backports. This role is a stripped down and adjusted version of [ansible-role-debian-backports](https://github.com/jnv/ansible-role-debian-backports)

# Installation

Add the following to `requirements.yml`:

```
- src: git@gitlab.com:carbonique/ansible-role-debian-backports.git
  scm: git
  name: debian-backports
  version: #Leave empty for latest. To download a specific version: use the tag as listed in repo
```

For system wide installation:
`ansible-galaxy install -r requirements.yml`

For installation to the current directory:
`ansible-galaxy install --roles-path . -r requirements.yml`

# Defaults & Variables

See defaults directory