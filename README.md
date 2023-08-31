# multipath

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/multipath)
[![General Workflow](https://github.com/rolehippie/multipath/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/multipath/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/multipath/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/multipath/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/multipath/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/multipath/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/multipath)](https://github.com/rolehippie/multipath/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.multipath-blue)](https://galaxy.ansible.com/rolehippie/multipath)

Ansible role to primary purge multipathd if not required.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [multipath_purge](#multipath_purge)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### multipath_purge

Purge all multipathd packages and dependencies

#### Default value

```YAML
multipath_purge: true
```

## Discovered Tags

**_multipath_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
