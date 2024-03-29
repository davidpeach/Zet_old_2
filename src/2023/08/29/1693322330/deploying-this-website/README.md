---
title: Deploying this website
date: 2023-08-29 16:18:50
timestamp: 1693322330
---

This website is a static website, which has been generated by [lupo](https://github.com/davidpeach/lupo).

With it being static html, its hosting requirements are pretty basic:

- Small, inexpensive server (I'm using the smallest available server on Digital Ocean).
- Nginx installed on server.
- SSL certificate installed.

## 3 Steps to setup my site from scratch
1. Instantiate the new server using Terraform - [Guide](/2023/08/29/1693323393/setting-up-a-digital-ocean-droplet-for-a-lupo-website-with-terraform/)
2. Installing the required software on that server using Ansible - [Guide](/2023/08/29/1693327115/using-ansible-to-prepare-a-digital-ocean-droplet-to-host-a-static-website/)
3. Building and deploying my site using Lupo - [Guide](/2023/08/30/1693385086/lupo-static-site-generator/)


