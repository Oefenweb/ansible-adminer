## adminer

[![Build Status](https://travis-ci.org/Oefenweb/ansible-adminer.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-adminer) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-adminer-blue.svg)](https://galaxy.ansible.com/Oefenweb/adminer)

Set up [adminer](http://www.adminer.org/) (Database management in a single PHP file).

#### Requirements

None

#### Variables

* `adminer_download_url`: [default: `https://www.adminer.org/latest.php`]: Download url
* `adminer_install_dirs`: [default: `[]`]: Directories to install adminer to (e.g. `/var/www`)

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
