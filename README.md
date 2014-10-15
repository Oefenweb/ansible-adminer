## adminer [![Build Status](https://travis-ci.org/Oefenweb/ansible-adminer.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-adminer)

Set up [adminer](http://www.adminer.org/) (Database management in a single PHP file).

#### Requirements

* `apache2`
* `php5`

#### Variables

* `adminer_install_dirs` [default: `[]`]: Directories to install adminer to (e.g. `/var/www`)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - adminer
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-adminer/issues)!
