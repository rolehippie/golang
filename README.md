# golang

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/golang)
[![General Workflow](https://github.com/rolehippie/golang/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/golang/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/golang/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/golang/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/golang/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/golang/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/golang)](https://github.com/rolehippie/golang/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.golang-blue)](https://galaxy.ansible.com/rolehippie/golang)

Ansible role to install golang programming language.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [golang_keyring](#golang_keyring)
  - [golang_purge](#golang_purge)
  - [golang_symlink](#golang_symlink)
  - [golang_versions](#golang_versions)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### golang_keyring

Path for the repository keyring

#### Default value

```YAML
golang_keyring: /usr/share/keyrings/golang-archive-keyring.gpg
```

### golang_purge

List of versions to purge

#### Default value

```YAML
golang_purge: []
```

### golang_symlink

Version to symlink binaries

#### Default value

```YAML
golang_symlink: '1.20'
```

### golang_versions

List of versions to install

#### Default value

```YAML
golang_versions:
  - '1.20'
```

## Discovered Tags

**_golang_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
