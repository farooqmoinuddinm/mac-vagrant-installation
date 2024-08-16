# Vagrant Setup with VMware Fusion

## Overview

This project sets up a Vagrant environment using VMware Fusion. The Vagrantfile is configured to create a virtual machine with Ubuntu 20.04, including provisioning for Apache.

## Requirements

- [Vagrant](https://www.vagrantup.com/downloads)
- [VMware Fusion](https://www.vmware.com/products/fusion.html)
- [Vagrant VMware Utility](https://www.vagrantup.com/docs/vmware/vagrant-vmware-utility.html)

## Installation

1. **Install Vagrant**:
   ```bash
   brew install --cask vagrant

2. **Install VMware Plugins for Vagrant**:
   ```bash
   vagrant plugin install vagrant-vmware-desktop
   vagrant plugin list

3. **Install VMtilites following below url**
   - [Vagrant VMware Utility](https://www.vagrantup.com/docs/vmware/vagrant-vmware-utility.html)

4. **Now run vagrant commands**:
   ```bash
   # add new arm based virtual box or download locally
   vagrant box add bento/ubuntu-20.04-arm64
   # you check list of boxes added in your local
   vagrant box list
   # start the vitual box
   vagrant up
   # Login into vagrant
   vagrant ssh
