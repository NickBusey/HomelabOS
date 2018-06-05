[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/1894/badge)](https://bestpractices.coreinfrastructure.org/projects/1894)

# HomelabOS

Your very own offline-first open-source data-center!

## Summary

A set of Ansible scripts to configure a Docker based Homelab server with all sorts of goodies.

## Goals

To make it easy for anyone to own all their data in an easy and secure way, without the need of cloud providers.

## Features

* One command depyloment
* Automated HTTPS endpoints (Coming Soon)
* Automated Backups (Coming Soon)
* Easy Restore (Coming Soon)
* Dynamic DNS Support (Coming Soon)

## Included Software

* [Home Assistant](https://www.home-assistant.io/) - Home Automation
* [Emby](https://emby.media/) - Media Player
* [Grafana](https://grafana.com/) - Pretty Graphs
* [Chronograf](https://www.influxdata.com/time-series-platform/chronograf/) - More pretty graphs. Easy data exploration.
* [InfluxDB](https://www.influxdata.com/time-series-platform/influxdb/) - Time Series Data Storage
* [Telegraf](https://www.influxdata.com/time-series-platform/telegraf/) - Server Statistics Reporting
* Documentation - Offline, searchable documentation via [MkDocs](https://www.mkdocs.org/).

### Coming Soon

* Gogs - Git Hosting
* NextCloud - Private Cloud Storage, Calendar, Contacts, LDAP, etc.
* uTorrent - Torrent Downloader
* BulletNotes - Note taking knowledgebase with kanban and calendar functionality.

## Requirements

A server running Ubuntu 18.04 accessible via ssh with a user that has sudo.

A domain configured with a `A` type DNS record of `*.yourdomain.com` pointed at your server's IP address.

Ports 80 and 443 punched through any firewalls and port forwarded at your server in question.

Ansible version 2.5+ installed on your computer (not the server).

## Installation

From your computer (not the server) run `ansible-playbook -i hosts homelabos.yml`.

## Contributing

Please do!

### Working locally on the documentation

Follow the [MkDocs Material Theme setup directions](https://squidfunk.github.io/mkdocs-material/getting-started/).

Then run `mkdocs serve`