# Ansible Role: Daemonize

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Installs [Daemonize](http://software.clapper.org/daemonize/), a tool for running commands as a Unix daemon.

## Requirements

Make sure you have `gcc` or other build tools installed (e.g. `yum install make automake gcc gcc-c++ kernel-devel` on RedHat, or `apt-get install build-essential` on Debian) prior to running this role, as it builds Daemonize from source.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    workspace: /root

The location where code will be downloaded and compiled.

    daemonize_version: 1.7.5

The daemonize release version to install.

    daemonize_install_path: "/usr"

The path where the compiled daemonize binary will be installed.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: nholuong.daemonize }

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟