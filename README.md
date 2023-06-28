# susecon-suma-aap-demo

This repository contains demo code for controlling SUMA / Uyuni using the [`stdevel.uyuni`](https://galaxy.ansible.com/stdevel/uyuni) Ansible collection.

It uses proper Ansible collections for:

- managing VMware vSphere snapshots
- (un)scheduling monitoring check_mk downtimes
- installing package update(s) and running OpenSCAP scans within SUMA / Uyuni

# Usage

Copy [`credentials.yml.demo`](credentials.yml.demo) and alter credentials. Change URL endpoints in the playbooks.

# Video

Check-out the following video for a demonstration:

[![IcingaBusylightAgent Alpha: Introduction and basic features](http://img.youtube.com/vi/OAQVpHQh1kc/0.jpg)](http://www.youtube.com/watch?v=OAQVpHQh1kc)
