# multipath

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/multipath) [![Build Status](https://img.shields.io/drone/build/rolehippie/multipath/master?logo=drone)](https://cloud.drone.io/rolehippie/multipath) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/multipath)](https://github.com/rolehippie/multipath/blob/master/LICENSE) 

Ansible role to primary purge multipathd if not required. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [multipath_purge](#multipath_purge)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### multipath_purge

Purge all multipathd packages and dependencies

#### Default value

```YAML
multipath_purge: true
```

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
