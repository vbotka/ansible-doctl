doctl (Digital Ocean Control)
=============================

[![Build Status](https://travis-ci.org/vbotka/ansible-doctl.svg?branch=master)](https://travis-ci.org/vbotka/ansible-doctl)

- [Ansible role](https://galaxy.ansible.com/vbotka/doctl/).
- Install *doctl* from [https://github.com/digitalocean/doctl](https://github.com/digitalocean/doctl/).
- *doctl* is a command line interface for the [DigitalOcean](https://www.digitalocean.com/) API.
- Optionaly install [dobro](https://gitlab.com/snoopdouglas/dobro) - management of droplets by tag.
- See [examples](https://github.com/vbotka/ansible-doctl/blob/master/contrib/).

Requirements
------------

None.


Role Variables
--------------

- doctl_source_version: "1.8.0"
- doctl_dobro: False

Dependencies
------------

None.

References
----------
- [doctl - README](https://github.com/digitalocean/doctl/blob/master/README.md)
- [doctl - The Command Line Interface to DigitalOcean](https://blog.digitalocean.com/introducing-doctl/)
- [doctl - How To Use Doctl, the Official DigitalOcean Command-Line Client](https://www.digitalocean.com/community/tutorials/how-to-use-doctl-the-official-digitalocean-command-line-client)
- [dobro - Manage DigitalOcean droplets by tag](https://gitlab.com/snoopdouglas/dobro)
- [dobro - PyPi](https://pypi.python.org/pypi/dobro/)

License
-------

[![license](https://img.shields.io/badge/license-BSD-red.svg)](https://www.freebsd.org/doc/en/articles/bsdl-gpl/article.html)

Author Information
------------------

[Vladimir Botka](https://botka.link)

TODO
----

- [Issue #26](https://github.com/snoopdouglas/dobro/issues/26)
