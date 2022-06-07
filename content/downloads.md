+++
title = "Downloads"
description = "Download Oxid Artefacts or learn how to use Oxid with composer"
date = "2022-05-31"
aliases = ["download","download-oxid","downloads"]
author = "Foo"
menu = "main"
weight = 200
+++

## Oxid Community Edition version 6.4.2
(latest version, published 2022-05-31

---

### Installation via composer

* Connect to your web server via SSH.
* Move to the doc root directory and use the following command: `composer create-project --no-dev oxid-esales/oxideshop-project my_oxid_eshop_project dev-b-6.4-ce`

*or*

### Manual installation

It is also possible to download, decompress and upload prepared artefacts. Take care you use the right artefact for the PHP version you use on your server:

* <https://github.com/FriendsOfOxid/Oxid-CE-artefacts/archive/refs/tags/v6.4.2_PHP8.0_001.tar.gz>
* <https://github.com/FriendsOfOxid/Oxid-CE-artefacts/archive/refs/tags/v6.4.2_PHP7.4_001.tar.gz>

---

### Run setup

* Map the top level domain of your web server to the directory *source/*.
* Fire up your browser and point it to this domain.
* Follow the steps of the setup routine.

---

### More ressources

* [Documentation](https://docs.oxid-esales.com)
* [Oxid on Github](https://github.com/OXID-esales/oxideshop_ce)
* [Get help on FOO Slack](https://join.slack.com/t/oxid-dev/shared_invite/enQtNDY1MDU0MzA3ODI4LTM3NDNlOTVjNzBhMWE3NzJmNDY0NzE0NWZiMDNjYzViNGFlODdiZTg5ODU5NzAwMDI3NDViOWI5NGE0NGNlYTc)

---

## Virtual Machines for Oxid

Often, it is helpful to work with prepared virtual machines that already have all dependencies and the right set of server environment ready to run for your local development environment. Grab one of them!

### OXID Dev Environment on Docker

As a developer you might want to use an SDK (Software Development Kit), an OXID development environment based on Docker incl. a collection of useful tools like tests or xDebug. The installation is very simple; however, this container is explicitly not suitable for productive use.
* <https://github.com/OXID-eSales/docker-eshop-sdk>

### Bitnami

Bitnami provides several stacks to run the latest OXID eShop versions, either at one of the big cloud services like Amazon or Google Cloud, or at Microsoft Azure. You also can download a virtual machine, a Docker container or even an executable web server for your PC, Mac or even Linux.

* <https://bitnami.com/stack/oxid>

### OXID eShop 6 Docker container

Run and deploy your OXID eShop installation within a docker container! Proudly provided by (@ProudCommerce)[https://www.proudcommerce.com]

* <https://github.com/proudcommerce/docker-oxid6>

### OXID Developer VM 

A vagrant box not only for OXID eShop including a collection of scripts and configuration files under LGPL. It lets you build a virtual machine as development environment for OXID eShop (all editions) or even for other web applications based on Vagrant within minutes. Please read the README for more detailed instructions.

* <https://github.com/OXID-eSales/oxvm_eshop/>
