st.locale
=========

[![Build Status](https://travis-ci.org/Stouts/st.locale.png)](https://travis-ci.org/Stouts/st.locale)

Ansible role which ensure the defined locales are exists.

#### Variables

```yaml
locale_locales: []         # List of locales to installed
```

#### Using

Just set `locale_locales` in your playbook file.

```yaml

locale_locales:
  - en_US.UTF-8
  - ru_RU.UTF-8
```

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/st.locale/issues)!
