# multipath

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/multipath) [![Testing Build](https://github.com/rolehippie/multipath/workflows/testing/badge.svg)](https://github.com/rolehippie/multipath/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/multipath/workflows/readme/badge.svg)](https://github.com/rolehippie/multipath/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/multipath/workflows/galaxy/badge.svg)](https://github.com/rolehippie/multipath/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/multipath)](https://github.com/rolehippie/multipath/blob/master/LICENSE)

Ansible role to primary purge multipathd if not required.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [multipath_purge](#multipath_purge)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

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
