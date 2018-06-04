# HomelabOS

An easy way to take control of your data.

A set of Ansible scripts to set up a Docker based Homelab server with all sorts of goodies.

## Goals

Make it easy for anyone to own all their data in an easy and secure way, without the need of cloud providers.

## Included

* Emby - Media Player
* Home Assistant - Home Automation
* Grafana - Pretty Graphs
* InfluxDB - Data Storage
* Telegraf - Server Statistics Reporting
* Gogs - Git Hosting
* NextCloud - Private Cloud Storage, Calendar, Contacts, LDAP, etc.
* uTorrent - Torrent Downloader

## Installation

Install Ubuntu 18.04

Create a user with passwordless sudo access and ssh key based access.

Run `ansible-playbook -i hosts homelabos.yml`

