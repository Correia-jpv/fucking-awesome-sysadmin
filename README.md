# Awesome Sysadmin

[![](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![](https://github.com/correia-jpv/fucking-awesome-sysadmin/actions/workflows/ci.yml/badge.svg)](https://github.com/correia-jpv/fucking-awesome-sysadmin/issues/416)

**A curated list of amazingly awesome Free and Open-Source sysadmin resources.** Please read the [Pull Request template](./.github/PULL_REQUEST_TEMPLATE.md) if you wish to add software and consider <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [donating](https://github.com/n1trux/awesome-donations)) to the FLOSS projects you use regularly. Please consider contributing to fix one of the pinned [issues](https://github.com/correia-jpv/fucking-awesome-sysadmin/issues) if your time allows.

--------------------

## Table of contents

- [Awesome Sysadmin](#awesome-sysadmin)
  - [Table of contents](#table-of-contents)
  - [Software](#software)
    - [Automation](#automation)
    - [Backups](#backups)
    - [Build and software organization tools](#build-and-software-organization-tools)
    - [ChatOps](#chatops)
    - [Cloud Computing](#cloud-computing)
    - [Code Review](#code-review)
    - [Configuration Management](#configuration-management)
    - [Configuration Management Database](#configuration-management-database)
    - [Continuous Integration \& Continuous Deployment](#continuous-integration-continuous-deployment)
    - [Control Panels](#control-panels)
    - [Databases](#databases)
    - [Deployment Automation](#deployment-automation)
    - [Diagramming](#diagramming)
    - [Distributed Filesystems](#distributed-filesystems)
    - [DNS - Control Panels \& Domain Management](#dns-control-panels-domain-management)
    - [DNS - Servers](#dns-servers)
    - [Editors](#editors)
    - [Identity Management](#identity-management)
    - [Identity Management - LDAP](#identity-management---ldap)
    - [Identity Management - Single Sign-On (SSO)](#identity-management---single-sign-on-sso)
    - [Identity Management - Tools and web interfaces](#identity-management---tools-and-web-interfaces)
    - [IT Asset Management](#it-asset-management)
    - [Log Management](#log-management)
    - [Mail Clients](#mail-clients)
    - [Metrics \& Metric Collection](#metrics-metric-collection)
    - [Miscellaneous](#miscellaneous)
    - [Monitoring](#monitoring)
    - [Network Configuration Management](#network-configuration-management)
    - [PaaS](#paas)
    - [Packaging](#packaging)
    - [Project Management](#project-management)
    - [Queuing](#queuing)
    - [Remote Desktop Clients](#remote-desktop-clients)
    - [Router](#router)
    - [Service Discovery](#service-discovery)
    - [Software Containers](#software-containers)
    - [Status Pages](#status-pages)
    - [Troubleshooting](#troubleshooting)
    - [Version control](#version-control)
    - [Virtualization](#virtualization)
    - [VPN](#vpn)
    - [Web](#web)
  - [List of Licenses](#list-of-licenses)
  - [External links](#external-links)
  - [Communities / Forums](#communities-forums)
  - [Repositories](#repositories)
  - [Websites](#websites)
  - [License](#license)

--------------------

## Software

### Automation

**[`^        back to top        ^`](#awesome-sysadmin)**

Build automation.

- 🌎 [Apache Ant](ant.apache.org/) - Automation build tool, similar to make, a library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. (<b><code>&nbsp;&nbsp;&nbsp;458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;451🍴</code></b> [Source Code](https://github.com/apache/ant))) `Apache-2.0` `Java`
- 🌎 [Apache Maven](maven.apache.org/) - Build automation tool mainly for Java. A software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information. (<b><code>&nbsp;&nbsp;4971⭐</code></b> <b><code>&nbsp;&nbsp;2830🍴</code></b> [Source Code](https://github.com/apache/maven))) `Apache-2.0` `Java`
- 🌎 [Bazel](www.bazel.io/) - A fast, scalable, multi-language and extensible build system. Used by Google. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/bazelbuild/bazel/))) `Apache-2.0` `Java`
- 🌎 [Bolt](www.puppet.com/community/open-source/bolt) - You can use Bolt to run one-off tasks, scripts to automate the provisioning and management of some nodes, you can use Bolt to move a step beyond scripts, and make them shareable. (<b><code>&nbsp;&nbsp;&nbsp;543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Source Code](https://github.com/puppetlabs/bolt))) `Apache-2.0` `Ruby`
- 🌎 [GNU Make](www.gnu.org/software/make/) - The most popular automation build tool for many purposes, make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.  🌎 [Source Code](git.savannah.gnu.org/cgit/make.git)) `GPL-3.0` `C`
- 🌎 [Gradle](gradle.org/) - Another build automation system. (<b><code>&nbsp;18407⭐</code></b> <b><code>&nbsp;&nbsp;5096🍴</code></b> [Source Code](https://github.com/gradle/gradle))) `Apache-2.0` `Groovy/Java`
- 🌎 [Rake](ruby.github.io/rake/) - Build automation tool similar to Make, written in and extensible in Ruby. (<b><code>&nbsp;&nbsp;2436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;630🍴</code></b> [Source Code](https://github.com/ruby/rake))) `MIT` `Ruby`


### Backups

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

_See also: <b><code>&nbsp;&nbsp;&nbsp;739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Restic's list of Linux backup software](https://github.com/restic/others))_

- 🌎 [Backupninja](0xacab.org/liberate/backupninja) - Lightweight, extensible meta-backup system, provides a centralized way to configure and coordinate many different backup utilities. `GPL-2.0` `Shell`
- 🌎 [Backrest](garethgeorge.github.io/backrest/) - Backrest is a web UI and orchestrator for restic backup. (<b><code>&nbsp;&nbsp;5517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [Source Code](https://github.com/garethgeorge/backrest))) `GPL-3.0` `Docker/Go`
- 🌎 [Bareos](www.bareos.org/) - Cross-network backup solution which preserves, archives, and recovers data from all major operating systems. (<b><code>&nbsp;&nbsp;1175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [Source Code](https://github.com/bareos/bareos))) `AGPL-3.0` `C++/C`
- 🌎 [Barman](pgbarman.org) - Backup and Recovery Manager for PostgreSQL. (<b><code>&nbsp;&nbsp;2733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [Source Code](https://github.com/EnterpriseDB/barman))) `GPL-3.0` `Python`
- 🌎 [BorgBackup](www.borgbackup.org/) - Deduplicating archiver with compression and authenticated encryption. (<b><code>&nbsp;13035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;827🍴</code></b> [Source Code](https://github.com/borgbackup/borg))) `BSD-3-Clause` `Python`
- 🌎 [Burp](burp.grke.org/) - Network backup and restore program. (<b><code>&nbsp;&nbsp;&nbsp;499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/grke/burp))) `AGPL-3.0` `C`
- [Dar](http://dar.linux.free.fr/) - Which stands for Disk ARchive, is a robust and rich featured archiving and backup software of the tar style. (<b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/Edrusb/DAR))) `GPL-2.0` `C++`
- 🌎 [Databasus](databasus.com/) - PostgreSQL, MySQL, MariaDB and MongoDB backup tool with web UI, external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management. (<b><code>&nbsp;&nbsp;5741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Source Code](https://github.com/databasus/databasus))) `Apache-2.0` `Docker`
- 🌎 [Duplicati](www.duplicati.com) - Backup client that securely stores encrypted, incremental, compressed backups on cloud storage services and remote file servers. (<b><code>&nbsp;14321⭐</code></b> <b><code>&nbsp;&nbsp;1027🍴</code></b> [Source Code](https://github.com/duplicati/duplicati))) `LGPL-2.1` `C#`
- 🌎 [Duplicity](duplicity.gitlab.io/) - Encrypted bandwidth-efficient backup using the rsync algorithm.  🌎 [Source Code](gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
- 🌎 [Minarca](minarca.org/) - Client–server backup platform with a centralized web console to manage and restore Linux, Windows, and macOS backups via GUI or CLI.  🌎 [Source Code](gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
- 🌎 [Portabase](portabase.io/) - Server dashboard tool that simplifies the backup and restoration of your database instances. (<b><code>&nbsp;&nbsp;&nbsp;505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/Portabase/portabase))) `Apache-2.0` `Docker`
- 🌎 [Proxmox Backup Server](www.proxmox.com/en/proxmox-backup-server) - Proxmox Backup Server is an enterprise-class, client-server backup solution thatis capable of backing up virtual machines, containers, and physical hosts.  🌎 [Source Code](git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`
- 🌎 [rclone](rclone.org/) - Command-line program to sync files and directories to and from different cloud storage providers.. (<b><code>&nbsp;55803⭐</code></b> <b><code>&nbsp;&nbsp;4940🍴</code></b> [Source Code](https://github.com/rclone/rclone))) `MIT` `Go`
- 🌎 [Rdiff-backup](rdiff-backup.net/) - Reverse differential backup tool, over a network or locally. (<b><code>&nbsp;&nbsp;1240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Source Code](https://github.com/rdiff-backup/rdiff-backup))) `GPL-2.0` `Python`
- 🌎 [Restic](restic.net/) - Easy, fast, verifiable, secure and efficient remote backup tool. (<b><code>&nbsp;32477⭐</code></b> <b><code>&nbsp;&nbsp;1722🍴</code></b> [Source Code](https://github.com/restic/restic))) `BSD-2-Clause` `Go`
- 🌎 [Rsnapshot](rsnapshot.org/) - Filesystem snapshot utility based on rsync. (<b><code>&nbsp;&nbsp;3595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Source Code](https://github.com/rsnapshot/rsnapshot))) `GPL-2.0` `Perl`
- <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Shield](https://github.com/starkandwayne/shield)) - A pluggable architecture for backup and restore of database systems. `MIT` `Go`
- 🌎 [UrBackup](www.urbackup.org/) - Client/Server Open Source Network Backup for Windows, MacOS and Linux. (<b><code>&nbsp;&nbsp;&nbsp;838⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [Source Code](https://github.com/uroni/urbackup_backend))) `AGPL-3.0` `C/C++`

### Build and software organization tools

**[`^        back to top        ^`](#awesome-sysadmin)**

Build and software organization tools.

- 🌎 [EasyBuild](easybuild.io/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way. (<b><code>&nbsp;&nbsp;&nbsp;441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;779🍴</code></b> [Source Code](https://github.com/easybuilders/easybuild-easyconfigs))) `GPL-2.0` `Python`
- 🌎 [Environment Modules](cea-hpc.github.io/modules/) - Environment Modules provides for the dynamic modification of a user's environment via modulefiles. (<b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [Source Code](https://github.com/cea-hpc/modules))) `GPL-2.0` `Tcl`
- 🌎 [Lmod](www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem. (<b><code>&nbsp;&nbsp;&nbsp;580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Source Code](https://github.com/TACC/Lmod))) `MIT` `Lua`
- 🌎 [Spack](spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. (<b><code>&nbsp;&nbsp;4960⭐</code></b> <b><code>&nbsp;&nbsp;2432🍴</code></b> [Source Code](https://github.com/spack/spack))) `MIT/Apache-2.0` `Python`


### ChatOps

**[`^        back to top        ^`](#awesome-sysadmin)**

Conversation-driven development and management.

_See also: 🌎 [/r/chatops](old.reddit.com/r/chatops)*

- 🌎 [Eggdrop](www.eggheads.org/) - The oldest Internet Relay Chat (IRC) bot still in active development. (<b><code>&nbsp;&nbsp;&nbsp;565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/eggheads/eggdrop))) `GPL-2.0` `C`
- 🌎 [Errbot](errbot.io/) - Plugin based chatbot designed to be easily deployable, extensible and maintainable. (<b><code>&nbsp;&nbsp;3272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [Source Code](https://github.com/errbotio/errbot))) `GPL-3.0` `Python`
- 🌎 [Hubot](hubot.github.com/) - A customizable, life embetterment robot. (<b><code>&nbsp;16777⭐</code></b> <b><code>&nbsp;&nbsp;3741🍴</code></b> [Source Code](https://github.com/hubotio/hubot))) `MIT` `Nodejs`


### Cloud Computing

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Cloud computing](en.wikipedia.org/wiki/Cloud_computing) is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user.

**Please visit 🌎 [Cloud Native Software Landscape](landscape.cncf.io/?group=projects-and-products&view-mode=card)**



### Code Review

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Code review](en.wikipedia.org/wiki/Code_review) is a software quality assurance activity in which one or several people check a program mainly by viewing and reading parts of its source code.

**Please visit 🌎 [awesome-selfhosted/Software Development - Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**



### Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Configuration management (CM)](en.wikipedia.org/wiki/Configuration_management) is a systems engineering process for establishing and maintaining consistency of a product's performance, functional, and physical attributes with its requirements, design, and operational information throughout its life.

- 🌎 [Ansible](www.ansible.com/) - Provisioning, configuration management, and application-deployment tool. (<b><code>&nbsp;68149⭐</code></b> <b><code>&nbsp;24188🍴</code></b> [Source Code](https://github.com/ansible/ansible))) `GPL-3.0` `Python`
- 🌎 [CFEngine](cfengine.com/) - Configuration management system for automated configuration and maintenance of large-scale computer systems. (<b><code>&nbsp;&nbsp;&nbsp;521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;197🍴</code></b> [Source Code](https://github.com/cfengine/core))) `GPL-3.0` `C`
- 🌎 [Chef](www.chef.io/products/chef-infra) - Configuration management tool using a pure-Ruby, domain-specific language (DSL) for writing system configuration "recipes". (<b><code>&nbsp;&nbsp;8348⭐</code></b> <b><code>&nbsp;&nbsp;2527🍴</code></b> [Source Code](https://github.com/chef/chef))) `Apache-2.0` `Ruby`
- 🌎 [cloud-init](cloud-init.io/) - Initialization tool to automate the configuration of VMs, cloud instances, or machines on a network. (<b><code>&nbsp;&nbsp;3612⭐</code></b> <b><code>&nbsp;&nbsp;1052🍴</code></b> [Source Code](https://github.com/canonical/cloud-init))) `GPL-3.0/Apache-2.0` `Python`
- 🌎 [Puppet](www.puppet.com/) - Software configuration management tool which includes its own declarative language to describe system configuration. (<b><code>&nbsp;&nbsp;7806⭐</code></b> <b><code>&nbsp;&nbsp;2207🍴</code></b> [Source Code](https://github.com/puppetlabs/puppet))) `Apache-2.0` `Ruby/C`
- 🌎 [Rudder](www.rudder.io/) - Scalable and dynamic configuration management system for patching, security & compliance, based on CFEngine. (<b><code>&nbsp;&nbsp;&nbsp;634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Source Code](https://github.com/Normation/rudder))) `GPL-3.0` `Scala`
- 🌎 [Salt](docs.saltproject.io/) - Event-driven IT automation, remote task execution, and configuration management software. (<b><code>&nbsp;15246⭐</code></b> <b><code>&nbsp;&nbsp;5570🍴</code></b> [Source Code](https://github.com/saltstack/salt))) `Apache-2.0` `Python`


### Configuration Management Database

**[`^        back to top        ^`](#awesome-sysadmin)**

Configuration management database (CMDB) software.

_Related: [IT Asset Management](#it-asset-management)_

- 🌎 [Collins](tumblr.github.io/collins/) - At Tumblr, it's the infrastructure source of truth and knowledge. (<b><code>&nbsp;&nbsp;&nbsp;575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Source Code](https://github.com/tumblr/collins))) `Apache-2.0` `Docker/Scala`
- 🌎 [i-doit](www.i-doit.org/) - IT Documentation and CMDB. `AGPL-3.0` `PHP`
- 🌎 [iTop](www.combodo.com/itop-193) - Complete ITIL web based service management tool.  🌎 [Source Code](sourceforge.net/projects/itop/files/)) `AGPL-3.0` `PHP`
- 🌎 [netbox](netbox.dev/) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.  🌎 [Demo](demo.netbox.dev/), <b><code>&nbsp;19912⭐</code></b> <b><code>&nbsp;&nbsp;2951🍴</code></b> [Source Code](https://github.com/netbox-community/netbox))) `Apache-2.0` `Python`


### Continuous Integration & Continuous Deployment

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) 🌎 [deployment](en.wikipedia.org/wiki/Continuous_deployment) software.

- 🌎 [ArgoCD](argo-cd.readthedocs.io/en/stable/) - Declarative, GitOps continuous delivery tool for Kubernetes. (<b><code>&nbsp;22167⭐</code></b> <b><code>&nbsp;&nbsp;6878🍴</code></b> [Source Code](https://github.com/argoproj/argo-cd))) `Apache-2.0` `Go`
- 🌎 [Buildbot](buildbot.net/) - Python-based toolkit for continuous integration. (<b><code>&nbsp;&nbsp;5433⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [Source Code](https://github.com/buildbot/buildbot))) `GPL-2.0` `Python`
- 🌎 [CDS](ovh.github.io/cds/) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform. (<b><code>&nbsp;&nbsp;4805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;453🍴</code></b> [Source Code](https://github.com/ovh/cds))) `BSD-3-Clause` `Go`
- 🌎 [Concourse](concourse-ci.org/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way.  🌎 [Demo](ci.concourse-ci.org/), <b><code>&nbsp;&nbsp;7768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;878🍴</code></b> [Source Code](https://github.com/concourse/concourse))) `Apache-2.0` `Go`
- 🌎 [drone](drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go. (<b><code>&nbsp;33835⭐</code></b> <b><code>&nbsp;&nbsp;2895🍴</code></b> [Source Code](https://github.com/drone/drone))) `Apache-2.0` `Go`
- 🌎 [Factor](www.factor.io/) - Programmatically define and run workflows to connect configuration management, source code management, build, continuous integration, continuous deployment and communication tools. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/factor-io/factor))) `MIT` `Ruby`
- 🌎 [GitLab CI](about.gitlab.com/solutions/continuous-integration/) - Gitlab's built-in, full-featured CI/CD solution.  🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- 🌎 [GoCD](www.go.cd/) - Continuous delivery server. (<b><code>&nbsp;&nbsp;7373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;981🍴</code></b> [Source Code](https://github.com/gocd/gocd))) `Apache-2.0` `Java/Ruby`
- 🌎 [Jenkins](jenkins-ci.org/) - Continuous Integration Server. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jenkinsci/jenkins/))) `MIT` `Java`
- 🌎 [Laminar](laminar.ohwg.net) - Fast, lightweight, simple and flexible Continuous Integration. (<b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Source Code](https://github.com/ohwgiles/laminar))) `GPL-3.0` `C++`
- <b><code>&nbsp;&nbsp;&nbsp;689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [PHP Censor](https://github.com/php-censor/php-censor)) - Open source self-hosted continuous integration server for PHP projects. `BSD-2-Clause` `PHP`
- 🌎 [Strider](strider-cd.github.io/) - Open Source Continuous Deployment / Continuous Integration platform. (<b><code>&nbsp;&nbsp;4581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [Source Code](https://github.com/Strider-CD/strider))) `MIT` `Nodejs`
- 🌎 [Terrateam](terrateam.io) - GitOps-first automation platform for Terraform and OpenTofu workflows with support for self-hosted runners. (<b><code>&nbsp;&nbsp;1191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/terrateamio/terrateam))) `MPL-2.0` `OCaml/Docker`
- 🌎 [werf](werf.io/) - Open Source CI/CD tool for building Docker images and deploying to Kubernetes via GitOps. (<b><code>&nbsp;&nbsp;4659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Source Code](https://github.com/werf/werf))) `Apache-2.0` `Go`
- 🌎 [Woodpecker](woodpecker-ci.org/) - Community fork of Drone that uses Docker containers. (<b><code>&nbsp;&nbsp;6562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [Source Code](https://github.com/woodpecker-ci/woodpecker))) `Apache-2.0` `Go`


### Control Panels

**[`^        back to top        ^`](#awesome-sysadmin)**

Web hosting and server or service control panels.

- 🌎 [Ajenti](ajenti.org/) - Control panel for Linux and BSD. (<b><code>&nbsp;&nbsp;7894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;870🍴</code></b> [Source Code](https://github.com/ajenti/ajenti))) `MIT` `Python/Shell`
- 🌎 [Cockpit](cockpit-project.org/) - Web-based graphical interface for servers. (<b><code>&nbsp;13223⭐</code></b> <b><code>&nbsp;&nbsp;1231🍴</code></b> [Source Code](https://github.com/cockpit-project/cockpit))) `LGPL-2.1` `C`
- 🌎 [Froxlor](froxlor.org/) - Lightweight server management software with Nginx and PHP-FPM support. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Froxlor/Froxlor/))) `GPL-2.0` `PHP`
- 🌎 [HestiaCP](hestiacp.com/) - Web server control panel (fork of VestaCP).  🌎 [Demo](demo.hestiacp.com:8083/login/), <b><code>&nbsp;&nbsp;4235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;852🍴</code></b> [Source Code](https://github.com/hestiacp/hestiacp))) `GPL-3.0` `PHP/Shell/Other`
- 🌎 [ISPConfig](www.ispconfig.org) - Manage Linux servers directly through your browser.  🌎 [Source Code](git.ispconfig.org/ispconfig/ispconfig3)) `BSD-3-Clause` `PHP`
- 🌎 [Sentora](sentora.org/) - Open-Source Web hosting control panel for Linux, BSD (fork of ZPanel). (<b><code>&nbsp;&nbsp;&nbsp;673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [Source Code](https://github.com/sentora/sentora-core))) `GPL-3.0` `PHP`
- 🌎 [Virtualmin](www.virtualmin.com/) - Powerful and flexible web hosting control panel for Linux and BSD systems. ([Source Code](https://github.com/virtualmin)) `GPL-3.0` `Shell/Perl/Other`
- 🌎 [Webmin](www.webmin.com/) - Web-based interface for system administration for Unix. (<b><code>&nbsp;&nbsp;5625⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;746🍴</code></b> [Source Code](https://github.com/webmin/webmin))) `BSD-3-Clause` `Perl`


### Databases

**[`^        back to top        ^`](#awesome-sysadmin)**

Database servers.

**Please visit 🌎 [dbdb.io - Database of Databases](dbdb.io/)**

_See also: 🌎 [awesome-selfhosted/Database Management](awesome-selfhosted.net/tags/database-management.html)_



### Deployment Automation

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools and scripts to support deployments to your servers.

- 🌎 [Capistrano](capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based). (<b><code>&nbsp;12926⭐</code></b> <b><code>&nbsp;&nbsp;1760🍴</code></b> [Source Code](https://github.com/capistrano/capistrano))) `MIT` `Ruby`
- 🌎 [CloudSlang](www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/CloudSlang/score))) `Apache-2.0` `Java`
- 🌎 [CloudStack](cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services. (<b><code>&nbsp;&nbsp;2818⭐</code></b> <b><code>&nbsp;&nbsp;1276🍴</code></b> [Source Code](https://github.com/apache/cloudstack))) `Apache-2.0` `Java/Python`
- 🌎 [Cobbler](cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. (<b><code>&nbsp;&nbsp;2745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;655🍴</code></b> [Source Code](https://github.com/cobbler/cobbler))) `GPL-2.0` `Python`
- 🌎 [Fabric](www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks. (<b><code>&nbsp;15399⭐</code></b> <b><code>&nbsp;&nbsp;1960🍴</code></b> [Source Code](https://github.com/fabric/fabric))) `BSD-2-Clause` `Python`
- 🌎 [FaynoSync](faynosync.com) - Self-hosted Dynamic Update Server with statistics, supporting multiple updaters. Flexible features for seamless app updates and insights.  (<b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/ku9nov/faynoSync)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Clients](https://github.com/ku9nov/faynoSync-dashboard))) `Apache-2.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Genesis](https://github.com/starkandwayne/genesis)) - A template framework for multi-environment BOSH deployments. `MIT` `Perl`
- 🌎 [munki](www.munki.org/munki/) - Webserver-based repository of packages and package metadata, that allows macOS administrators to manage software installs. (<b><code>&nbsp;&nbsp;3357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [Source Code](https://github.com/munki/munki))) `Apache-2.0` `Python`
- 🌎 [Overcast](andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH. (<b><code>&nbsp;&nbsp;&nbsp;486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/andrewchilds/overcast))) `MIT` `Nodejs`


### Diagramming

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools used to create diagrams of networks, flows, etc.

- 🌎 [Diagrams.net](app.diagrams.net/) - A.K.A. 🌎 [Draw.io](app.diagrams.net/). Easy to use Diagram UI with a plethora of templates. (<b><code>&nbsp;&nbsp;3815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;671🍴</code></b> [Source Code](https://github.com/jgraph/drawio))) `Apache-2.0` `JavaScript/Docker`
- 🌎 [Kroki](kroki.io) - API for generating diagrams from textual descriptions. (<b><code>&nbsp;&nbsp;3988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [Source Code](https://github.com/yuzutech/kroki))) `MIT` `Java`
- 🌎 [Mermaid](mermaid-js.github.io/mermaid-live-editor/) - Javascript module with a unique, easy, shorthand syntax. Integrates into several other tools like Grafana. (<b><code>&nbsp;&nbsp;6238⭐</code></b> <b><code>&nbsp;&nbsp;1032🍴</code></b> [Source Code](https://github.com/mermaid-js/mermaid-live-editor))) `MIT` `Nodejs/Docker`


### Distributed Filesystems

**[`^        back to top        ^`](#awesome-sysadmin)**

Network distributed filesystems.

_See also: 🌎 [awesome-selfhosted/File Transfer - Object Storage & File Servers](awesome-selfhosted.net/tags/file-transfer---object-storage--file-servers.html)_

- 🌎 [Ceph](ceph.com/en/) - Distributed object, block, and file storage platform. (<b><code>&nbsp;16283⭐</code></b> <b><code>&nbsp;&nbsp;6307🍴</code></b> [Source Code](https://github.com/ceph/ceph))) `LGPL-3.0` `C++`
- 🌎 [DRBD](linbit.com/drbd/) - Distributed replicated storage system, implemented as a Linux kernel driver. (<b><code>&nbsp;&nbsp;&nbsp;678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Source Code](https://github.com/LINBIT/drbd))) `GPL-2.0` `C`
- 🌎 [GlusterFS](www.gluster.org/) - Software-defined distributed storage that can scale to several petabytes, with interfaces for object, block and file storage. (<b><code>&nbsp;&nbsp;5149⭐</code></b> <b><code>&nbsp;&nbsp;1118🍴</code></b> [Source Code](https://github.com/gluster/glusterfs))) `GPL-2.0/LGPL-3.0` `C`
- 🌎 [Hadoop Distributed Filesystem (HDFS)](hadoop.apache.org/) - Distributed file system that provides high-throughput access to application data. (<b><code>&nbsp;15489⭐</code></b> <b><code>&nbsp;&nbsp;9198🍴</code></b> [Source Code](https://github.com/apache/hadoop))) `Apache-2.0` `Java`
- 🌎 [JuiceFS](juicefs.com/) - Distributed POSIX file system built on top of Redis and S3. (<b><code>&nbsp;13282⭐</code></b> <b><code>&nbsp;&nbsp;1166🍴</code></b> [Source Code](https://github.com/juicedata/juicefs))) `Apache-2.0` `Go`
- <b><code>&nbsp;16935⭐</code></b> <b><code>&nbsp;&nbsp;3140🍴</code></b> [Kubo](https://github.com/ipfs/kubo)) - Implementation of IPFS, a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files. `Apache-2.0/MIT` `Go`
- 🌎 [LeoFS](leo-project.net) - Highly available, distributed, replicated eventually consistent object/blob store. (<b><code>&nbsp;&nbsp;1589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Source Code](https://github.com/leo-project/leofs))) `Apache-2.0` `Erlang`
- 🌎 [Lustre](www.lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.  🌎 [Source Code](git.whamcloud.com/?p=fs/lustre-release.git;a=summary)) `GPL-2.0` `C`
- 🌎 [Minio](min.io/) - High-performance, S3 compatible object store built for large scale AI/ML, data lake and database workloads. (<b><code>&nbsp;60401⭐</code></b> <b><code>&nbsp;&nbsp;7158🍴</code></b> [Source Code](https://github.com/minio/minio))) `AGPL-3.0` `Go`
- 🌎 [MooseFS](moosefs.com/) - Fault tolerant, network distributed file system. (<b><code>&nbsp;&nbsp;1948⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [Source Code](https://github.com/moosefs/moosefs))) `GPL-2.0` `C`
- 🌎 [OpenAFS](www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.  🌎 [Source Code](git.openafs.org/?p=openafs.git;a=summary)) `IPL-1.0` `C`
- 🌎 [Openstack Swift](docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.  🌎 [Source Code](opendev.org/openstack/swift)) `Apache-2.0` `Python`
- 🌎 [Perkeep](perkeep.org/) - A set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data (previously Camlistore). (<b><code>&nbsp;&nbsp;7103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;481🍴</code></b> [Source Code](https://github.com/perkeep/perkeep))) `Apache-2.0` `C`
- 🌎 [TahoeLAFS](tahoe-lafs.org/trac/tahoe-lafs) - Secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system. (<b><code>&nbsp;&nbsp;1393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [Source Code](https://github.com/tahoe-lafs/tahoe-lafs))) `GPL-2.0` `Python`
- 🌎 [XtreemFS](www.xtreemfs.org/) - Distributed, replicated and fault-tolerant file system for federated IT infrastructures.. (<b><code>&nbsp;&nbsp;&nbsp;345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Source Code](https://github.com/xtreemfs/xtreemfs))) `BSD-3-Clause` `Java`


### DNS - Control Panels & Domain Management

**[`^        back to top        ^`](#awesome-sysadmin)**

DNS server control panels, web interfaces and domain management tools.

_Related: [DNS - Servers](#dns---servers)_

_See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)_

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Atomia DNS](https://github.com/atomia/atomiadns/)) - DNS management system. `ISC` `Perl`
- 🌎 [Designate](wiki.openstack.org/wiki/Designate) - DNSaaS services for OpenStack.  🌎 [Source Code](opendev.org/openstack/designate)) `Apache-2.0` `Python`
- 🌎 [DNSControl](stackexchange.github.io/dnscontrol/) - Synchronize your DNS to multiple providers from a simple DSL. (<b><code>&nbsp;&nbsp;3763⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;484🍴</code></b> [Source Code](https://github.com/StackExchange/dnscontrol))) `MIT` `Go/Docker`
- 🌎 [DomainMOD](domainmod.org) - Manage your domains and other internet assets in a central location. (<b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Source Code](https://github.com/domainmod/domainmod))) `GPL-3.0` `PHP`
- 🌎 [nsupdate.info](www.nsupdate.info/) - Dynamic DNS service.  🌎 [Demo](www.nsupdate.info/account/register/), <b><code>&nbsp;&nbsp;1121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/nsupdate-info/nsupdate.info))) `BSD-3-Clause` `Python`
- <b><code>&nbsp;&nbsp;3644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [octoDNS](https://github.com/github/octodns)) - DNS as code - Tools for managing DNS across multiple providers. `MIT` `Python`
- 🌎 [Poweradmin](www.poweradmin.org/) - Web-based DNS control panel for PowerDNS server. (<b><code>&nbsp;&nbsp;&nbsp;832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [Source Code](https://github.com/poweradmin/poweradmin))) `GPL-3.0` `PHP`
- 🌎 [SPF Toolbox](spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. (<b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Source Code](https://github.com/charlesabarnes/SPFtoolbox))) `MIT` `PHP`


### DNS - Servers

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [DNS](en.wikipedia.org/wiki/Name_server) servers.

_Related: [DNS - Control Panels & Domain Management](#dns---control-panels--domain-management)_

_See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)_

- 🌎 [Bind](www.isc.org/bind/) - Versatile, classic, complete name server software.  🌎 [Source Code](gitlab.isc.org/isc-projects/bind9)) `MPL-2.0` `C`
- 🌎 [CoreDNS](coredns.io/) - Flexible DNS server. (<b><code>&nbsp;13942⭐</code></b> <b><code>&nbsp;&nbsp;2412🍴</code></b> [Source Code](https://github.com/coredns/coredns))) `Apache-2.0` `Go`
- 🌎 [djbdns](cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.  🌎 [Source Code](salsa.debian.org/debian/djbdns)) `CC0-1.0` `C`
- 🌎 [dnsmasq](www.thekelleys.org.uk/dnsmasq/doc.html) - Provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot.  🌎 [Source Code](thekelleys.org.uk/gitweb/?p=dnsmasq.git;a=tree)) `GPL-2.0` `C`
- 🌎 [Knot](www.knot-dns.cz/) - High performance authoritative-only DNS server.  🌎 [Source Code](gitlab.nic.cz/knot/knot-dns)) `GPL-3.0` `C`
- 🌎 [NSD](www.nlnetlabs.nl/projects/nsd/about/) - Authoritative DNS name server developed speed, reliability, stability and security. (<b><code>&nbsp;&nbsp;&nbsp;538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Source Code](https://github.com/NLnetLabs/nsd))) `BSD-3-Clause` `C`
- 🌎 [PowerDNS Authoritative Server](doc.powerdns.com/authoritative/) - Versatile nameserver which supports a large number of backends. (<b><code>&nbsp;&nbsp;4284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;982🍴</code></b> [Source Code](https://github.com/PowerDNS/pdns))) `GPL-2.0` `C++`
- 🌎 [Unbound](nlnetlabs.nl/projects/unbound/about/) - Validating, recursive, and caching DNS resolver. (<b><code>&nbsp;&nbsp;4284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [Source Code](https://github.com/NLnetLabs/unbound))) `BSD-3-Clause` `C`
- 🌎 [Yadifa](www.yadifa.eu/) - Clean, small, light and RFC-compliant name server implementation developed from scratch by .eu. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/yadifa/yadifa))) `BSD-3-Clause` `C`


### Editors

**[`^        back to top        ^`](#awesome-sysadmin)**

Open-source code editors.

- <b><code>&nbsp;&nbsp;&nbsp;779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Atom Community](https://github.com/atom-community/atom)) - A fork of <b><code>&nbsp;60992⭐</code></b> <b><code>&nbsp;17279🍴</code></b> [atom](https://github.com/atom/atom)) A hackable text editor from Github. `MIT` `JavaScript`
- 🌎 [Brackets](brackets.io/) - Code editor for web designers and front-end developers. (<b><code>&nbsp;&nbsp;1496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [Source Code](https://github.com/brackets-cont/brackets))) `MIT` `JavaScript`
- 🌎 [Eclipse](www.eclipse.org/) - IDE written in Java with an extensible plug-in system.  🌎 [Source Code](git.eclipse.org/c/)) `EPL-1.0` `Java`
- 🌎 [Geany](www.geany.org/) - GTK2 text editor. (<b><code>&nbsp;&nbsp;3547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;646🍴</code></b> [Source Code](https://github.com/geany/geany))) `GPL-2.0` `C/C++`
- 🌎 [GNU Emacs](www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more. (<b><code>&nbsp;&nbsp;4963⭐</code></b> <b><code>&nbsp;&nbsp;1355🍴</code></b> [Source Code](https://github.com/emacs-mirror/emacs))) `GPL-3.0` `C`
- [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview. (<b><code>&nbsp;&nbsp;1732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Source Code](https://github.com/rhiokim/haroopad))) `GPL-3.0` `JavaScript`
- <b><code>&nbsp;&nbsp;&nbsp;210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [jotgit](https://github.com/jdleesmiller/jotgit)) - Git-backed real-time collaborative code editing. `MIT` `Nodejs`
- 🌎 [KDevelop](www.kdevelop.org/) - IDE by the people behind KDE.  🌎 [Source Code](invent.kde.org/kdevelop/kdevelop)) `GFDL-1.2` `C++`
- 🌎 [Micro](micro-editor.github.io/) - A modern and intuitive terminal-based text editor. (<b><code>&nbsp;28063⭐</code></b> <b><code>&nbsp;&nbsp;1288🍴</code></b> [Source Code](https://github.com/zyedidia/micro))) `MIT` `Go`
- 🌎 [Nano](nano-editor.org) - Easy to use, customizable text editor.  🌎 [Source Code](git.savannah.gnu.org/cgit/nano.git/tree/)) `GPL-3.0` `C`
- 🌎 [Notepad++](notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows. (<b><code>&nbsp;27252⭐</code></b> <b><code>&nbsp;&nbsp;5119🍴</code></b> [Source Code](https://github.com/notepad-plus-plus/notepad-plus-plus))) `GPL-2.0` `C++`
- 🌎 [TextMate](macromates.com/) - A graphical text editor for OS X. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/textmate/textmate/))) `GPL-3.0` `C++`
- 🌎 [Vim](www.vim.org) - A highly configurable text editor built to enable efficient editing. (<b><code>&nbsp;39930⭐</code></b> <b><code>&nbsp;&nbsp;5988🍴</code></b> [Source Code](https://github.com/vim/vim))) `Vim` `C`
- 🌎 [VSCodium](vscodium.com/) - An open source cross-platform extensible code editor based on 🌎 [VS Code by Microsoft](code.visualstudio.com/) removing their non-free additions. (<b><code>&nbsp;30314⭐</code></b> <b><code>&nbsp;&nbsp;1574🍴</code></b> [Source Code](https://github.com/VSCodium/vscodium))) `MIT` `TypeScript`


### Identity Management

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Identity management](en.wikipedia.org/wiki/Identity_management) (IdM), also known as identity and access management (IAM or IdAM), is a framework of policies and technologies to ensure that the right users (that are part of the ecosystem connected to or within an enterprise) have the appropriate access to technology resources.

**Please visit [Identity Management - LDAP](#identity-management---ldap), [Identity Management - Tools and web interfaces](#identity-management---tools-and-web-interfaces), [Identity Management - Single Sign-On SSO](#identity-management---single-sign-on-sso)**



### Identity Management - LDAP

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Lightweight Directory Access Protocol (LDAP)](en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) is an open, vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network.

- 🌎 [389 Directory Server](www.port389.org/) - Enterprise-class Open Source LDAP server for Linux. (<b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Source Code](https://github.com/389ds/389-ds-base))) `GPL-3.0` `C`
- 🌎 [Apache Directory Server](directory.apache.org/apacheds/) - Extensible and embeddable directory server, certified LDAPv3 compatible, with Kerberos 5 and Change Password Protocol support, triggers, stored procedures, queues and views. (<b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Source Code](https://github.com/apache/directory-server))) `Apache-2.0` `Java`
- 🌎 [FreeIPA](www.freeipa.org/) - Integrated security information management solution combining Linux (Fedora), 389 Directory Server, Kerberos, NTP, DNS, and Dogtag Certificate System (web interface and command-line administration tools).  🌎 [Source Code](pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
- 🌎 [FreeRADIUS](freeradius.org/) - Multi-protocol policy server (radiusd) that implements RADIUS, DHCP, BFD, and ARP and associated client/PAM library/Apache module. (<b><code>&nbsp;&nbsp;2476⭐</code></b> <b><code>&nbsp;&nbsp;1175🍴</code></b> [Source Code](https://github.com/FreeRADIUS/freeradius-server))) `GPL-2.0` `C`
- <b><code>&nbsp;&nbsp;6055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [lldap](https://github.com/nitnelave/lldap)) - Light (simplified) LDAP implementation with a simple, intuitive web interface and GraphQL support. `GPL-3.0` `Rust`
- 🌎 [OpenLDAP](www.openldap.org/) - Open-source implementation of the Lightweight Directory Access Protocol (server, libraries and clients).  🌎 [Source Code](git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`


### Identity Management - Single Sign-On (SSO)

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Single sign-on (SSO)](en.wikipedia.org/wiki/Single_sign-on) is an authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems. 

- 🌎 [Authelia](www.authelia.com/) - The Single Sign-On Multi-Factor portal for web apps. (<b><code>&nbsp;27007⭐</code></b> <b><code>&nbsp;&nbsp;1349🍴</code></b> [Source Code](https://github.com/authelia/authelia))) `Apache-2.0` `Go`
- 🌎 [Authentik](goauthentik.io/) - Flexible identity provider with support for different protocols. (OAuth 2.0, SAML, LDAP and Radius). (<b><code>&nbsp;20343⭐</code></b> <b><code>&nbsp;&nbsp;1492🍴</code></b> [Source Code](https://github.com/goauthentik/authentik))) `MIT` `Python`
- 🌎 [KeyCloak](www.keycloak.org) - Open Source Identity and Access Management. (<b><code>&nbsp;33089⭐</code></b> <b><code>&nbsp;&nbsp;8086🍴</code></b> [Source Code](https://github.com/keycloak/keycloak))) `Apache-2.0` `Java`


### Identity Management - Tools and web interfaces

**[`^        back to top        ^`](#awesome-sysadmin)**

Miscellaneous utilities and web interfaces for identity management systems.

- 🌎 [BounCA](bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.  🌎 [Source Code](gitlab.com/bounca/bounca/)) `Apache-2.0` `Python`
- <b><code>&nbsp;&nbsp;4400⭐</code></b> <b><code>&nbsp;&nbsp;1227🍴</code></b> [easy-rsa](https://github.com/OpenVPN/easy-rsa)) - Bash script to build and manage a PKI CA. `GPL-2.0` `Shell`
- 🌎 [Fusion Directory](www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP. (<b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/fusiondirectory/fusiondirectory))) `GPL-2.0` `PHP`
- 🌎 [LDAP Account Manager (LAM)](www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/LDAPAccountManager/lam/))) `GPL-3.0` `PHP`
- 🌎 [Libravatar](www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.  🌎 [Source Code](git.linux-kernel.at/oliver/ivatar/)) `AGPL-3.0` `Python`
- 🌎 [Pomerium](www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp. (<b><code>&nbsp;&nbsp;4687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Source Code](https://github.com/pomerium/pomerium))) `Apache-2.0` `Docker/Go`
- 🌎 [Samba](www.samba.org/) - Active Directory and CIFS protocol implementation.  🌎 [Source Code](download.samba.org/pub/samba/)) `GPL-3.0` `C`
- 🌎 [Smallstep Certificates](smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management. (<b><code>&nbsp;&nbsp;8273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [Source Code](https://github.com/smallstep/certificates))) `Apache-2.0` `Go`
- 🌎 [ZITADEL](zitadel.com/) - Cloud-native Identity & Access Management solution providing a platform for secure authentication, authorization and identity management. (<b><code>&nbsp;13117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;949🍴</code></b> [Source Code](https://github.com/zitadel/zitadel))) `Apache-2.0` `Go/Docker/K8S`


### IT Asset Management

**[`^        back to top        ^`](#awesome-sysadmin)**

IT 🌎 [asset management](en.wikipedia.org/wiki/Asset_management) software.

- 🌎 [GLPI](www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface. (<b><code>&nbsp;&nbsp;5651⭐</code></b> <b><code>&nbsp;&nbsp;1620🍴</code></b> [Source Code](https://github.com/glpi-project/glpi))) `GPL-3.0` `PHP`
- 🌎 [OCS Inventory NG](ocsinventory-ng.org/) - Asset management and deployment solution for all devices in your IT Department. ([Source Code](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
- 🌎 [OPSI](www.opsi.org) - Hardware and software inventory, client management, deployment, and patching for Linux and Windows. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/opsi-org/))) `GPL-3.0/AGPL-3.0` `OVF/Python`
- 🌎 [RackTables](racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.  🌎 [Demo](www.racktables.org/demo.php), <b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Source Code](https://github.com/RackTables/racktables))) `GPL-2.0` `PHP`
- 🌎 [Ralph](ralph.allegro.tech/) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks. (<b><code>&nbsp;&nbsp;2455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;592🍴</code></b> [Demo](https://github.com/allegro/ralph#live-demo)), <b><code>&nbsp;&nbsp;2455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;592🍴</code></b> [Source Code](https://github.com/allegro/ralph))) `Apache-2.0` `Python/Docker`
- 🌎 [Snipe IT](snipeitapp.com/) - Asset & license management software. (<b><code>&nbsp;13466⭐</code></b> <b><code>&nbsp;&nbsp;3755🍴</code></b> [Source Code](https://github.com/snipe/snipe-it))) `AGPL-3.0` `PHP`


### Log Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Log management tools: collect, parse, visualize...

- 🌎 [Fluentd](www.fluentd.org/) - Data collector for unified logging layer. (<b><code>&nbsp;13502⭐</code></b> <b><code>&nbsp;&nbsp;1383🍴</code></b> [Source Code](https://github.com/fluent/fluentd))) `Apache-2.0` `Ruby`
- 🌎 [Flume](flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. (<b><code>&nbsp;&nbsp;2560⭐</code></b> <b><code>&nbsp;&nbsp;1555🍴</code></b> [Source Code](https://github.com/apache/flume))) `Apache-2.0` `Java`
- 🌎 [GoAccess](goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. (<b><code>&nbsp;20269⭐</code></b> <b><code>&nbsp;&nbsp;1174🍴</code></b> [Source Code](https://github.com/allinurl/goaccess))) `MIT` `C`
- 🌎 [Loki](grafana.com/oss/loki/) - Log aggregation system designed to store and query logs from all your applications and infrastructure. (<b><code>&nbsp;27725⭐</code></b> <b><code>&nbsp;&nbsp;3943🍴</code></b> [Source Code](https://github.com/grafana/loki))) `AGPL-3.0` `Go`
- 🌎 [rsyslog](www.rsyslog.com/) - Rocket-fast system for log processing. (<b><code>&nbsp;&nbsp;2261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;709🍴</code></b> [Source Code](https://github.com/rsyslog/rsyslog))) `GPL-3.0` `C`


### Mail Clients

**[`^        back to top        ^`](#awesome-sysadmin)**

An 🌎 [email client](en.wikipedia.org/wiki/Email_client), email reader or, more formally, message user agent (MUA) or mail user agent is a computer program used to access and manage a user's email. 

- 🌎 [aerc](aerc-mail.org/) - Terminal MUA with a focus on plaintext and features for developers.  🌎 [Source Code](git.sr.ht/~rjarry/aerc)) `MIT` `Go`
- [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.  🌎 [Source Code](git.claws-mail.org/?p=claws.git;a=tree)) `GPL-3.0` `C`
- [ImapSync](http://imapsync.lamiral.info/) - Simple IMAP migration tool for copying mailboxes to other servers. (<b><code>&nbsp;&nbsp;3955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;515🍴</code></b> [Source Code](https://github.com/imapsync/imapsync))) `NLPL` `Perl`
- [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.  🌎 [Source Code](gitlab.com/muttmua/mutt)) `GPL-2.0` `C`
- 🌎 [Sylpheed](sylpheed.sraoss.jp/en/) - Still developed predecessor to Claws Mail, lightweight mail client. (<b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/sylpheed-mail/sylpheed))) `GPL-2.0` `C`
- 🌎 [Thunderbird](www.thunderbird.net/) - Free email application that's easy to set up and customize.  🌎 [Source Code](hg.mozilla.org/comm-central/file)) `MPL-2.0` `C/C++`


### Metrics & Metric Collection

**[`^        back to top        ^`](#awesome-sysadmin)**

Metric gathering and display software.

_Related: [Databases](#databases), [Monitoring](#monitoring)_

- 🌎 [Beats](www.elastic.co/beats/) - Single-purpose data shippers that send data from hundreds or thousands of machines and systems to Logstash or Elasticsearch. (<b><code>&nbsp;12599⭐</code></b> <b><code>&nbsp;&nbsp;4991🍴</code></b> [Source Code](https://github.com/elastic/beats))) `Apache-2.0` `Go`
- 🌎 [Collectd](collectd.org/) - System statistics collection daemon. (<b><code>&nbsp;&nbsp;3346⭐</code></b> <b><code>&nbsp;&nbsp;1252🍴</code></b> [Source Code](https://github.com/collectd/collectd))) `MIT` `C`
- <b><code>&nbsp;&nbsp;1761⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;598🍴</code></b> [Diamond](https://github.com/python-diamond/Diamond)) - Daemon that collects system metrics and publishes them to Graphite (and others). `MIT` `Python`
- 🌎 [Grafana](grafana.com/) - A Graphite & InfluxDB Dashboard and Graph Editor. (<b><code>&nbsp;72442⭐</code></b> <b><code>&nbsp;13498🍴</code></b> [Source Code](https://github.com/grafana/grafana))) `AGPL-3.0` `Go`
- 🌎 [Graphite](graphite.readthedocs.org/en/latest/) - Scalable graphing server. (<b><code>&nbsp;&nbsp;6069⭐</code></b> <b><code>&nbsp;&nbsp;1255🍴</code></b> [Source Code](https://github.com/graphite-project/graphite-web))) `Apache-2.0` `Python`
- 🌎 [RRDtool](oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data. (<b><code>&nbsp;&nbsp;1083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Source Code](https://github.com/oetiker/rrdtool-1.x))) `GPL-2.0` `C`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Statsd](https://github.com/etsy/statsd/)) - Daemon that listens for statistics like counters and timers, sent over UDP or TCP, and sends aggregates to one or more pluggable backend services. `MIT` `Nodejs`
- [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - Gathers data from local collectors and pushes the data to OpenTSDB. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/OpenTSDB/tcollector/))) `LGPL-3.0/GPL-3.0` `Python`
- <b><code>&nbsp;16734⭐</code></b> <b><code>&nbsp;&nbsp;5765🍴</code></b> [Telegraf](https://github.com/influxdata/telegraf)) - Plugin-driven server agent for collecting, processing, aggregating, and writing metrics. `MIT` `Go`


### Miscellaneous

**[`^        back to top        ^`](#awesome-sysadmin)**

Software that does not fit in another section.

- 🌎 [Chocolatey](chocolatey.org/) - The package manager for Windows. (<b><code>&nbsp;11267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;933🍴</code></b> [Source Code](https://github.com/chocolatey/choco))) `Apache-2.0` `C#/PowerShell`
- 🌎 [Clonezilla](clonezilla.org/) - Partition and disk imaging/cloning program.  🌎 [Source Code](clonezilla.org/downloads/src/)) `GPL-2.0` `Perl/Shell/Other`
- 🌎 [DadaMail](dadamailproject.com/) - Mailing List Manager, written in Perl.  🌎 [Source Code](sourceforge.net/projects/dadamail/files/)) `GPL-2.0` `Perl`
- 🌎 [Fog](www.fogproject.org/) - Cloning/imaging solution/rescue suite. (<b><code>&nbsp;&nbsp;1510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [Source Code](https://github.com/FOGProject/fogproject))) `GPL-3.0` `PHP/Shell`
- 🌎 [phpList](www.phplist.org/) - Newsletter and email marketing software. (<b><code>&nbsp;&nbsp;&nbsp;833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [Source Code](https://github.com/phpList/phplist3))) `AGPL-3.0` `PHP`


### Monitoring

**[`^        back to top        ^`](#awesome-sysadmin)**

Monitoring software.

_Related: [Metrics & Metric Collection](#metrics--metric-collection)_

- [Adagios](http://adagios.org/) - Web based Nagios interface for configuration and monitoring (replacement to the standard interface), and a REST interface. (<b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Source Code](https://github.com/opinkerfi/adagios))) `AGPL-3.0` `Docker/Python`
- 🌎 [Alerta](alerta.io/) - Distributed, scalable and flexible monitoring system. (<b><code>&nbsp;&nbsp;2501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Source Code](https://github.com/alerta/alerta))) `Apache-2.0` `Python`
- 🌎 [Beszel](beszel.dev/) - Lightweight server monitoring platform that includes Docker statistics, historical data, and alert functions. (<b><code>&nbsp;19703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;653🍴</code></b> [Source Code](https://github.com/henrygd/beszel))) `MIT` `Go`
- 🌎 [Cacti](www.cacti.net) - Web-based network monitoring and graphing tool. (<b><code>&nbsp;&nbsp;1807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [Source Code](https://github.com/Cacti/cacti))) `GPL-2.0` `PHP`
- <b><code>&nbsp;18923⭐</code></b> <b><code>&nbsp;&nbsp;2461🍴</code></b> [cadvisor](https://github.com/google/cadvisor)) - Analyzes resource usage and performance characteristics of running containers. `Apache-2.0` `Go`
- 🌎 [checkmk](checkmk.com/) - Comprehensive solution for monitoring of applications, servers, and networks. (<b><code>&nbsp;&nbsp;2210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [Source Code](https://github.com/Checkmk/checkmk))) `GPL-2.0` `Python/PHP`
- <b><code>&nbsp;&nbsp;3356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [dashdot](https://github.com/MauriceNino/dashdot)) - A simple, modern server dashboard for smaller private servers.  🌎 [Demo](dash.mauz.dev/)) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [EdMon](https://github.com/Edraens/EdMon)) - A command-line monitoring application helping you to check that your hosts and services are available, with notifications support. `MIT` `Java`
- 🌎 [eZ Server Monitor](www.ezservermonitor.com) - A lightweight and simple dashboard monitor for Linux, available in Web and Bash application. (<b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/shevabam/ezservermonitor-web))) `GPL-3.0` `PHP/Shell`
- 🌎 [glances](nicolargo.github.io/glances/) - Open-source, cross-platform real-time monitoring tool with CLI and web dashboard interfaces and many exporting options. (<b><code>&nbsp;31835⭐</code></b> <b><code>&nbsp;&nbsp;1691🍴</code></b> [Source Code](https://github.com/nicolargo/glances))) `GPL-3.0` `Python`
- 🌎 [Healthchecks](healthchecks.io/docs/self_hosted/) - Monitoring for cron jobs, background services and scheduled tasks. (<b><code>&nbsp;&nbsp;9913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;944🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks))) `BSD-3-Clause` `Python`
- 🌎 [Icinga](www.icinga.com/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring. (<b><code>&nbsp;&nbsp;2178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;599🍴</code></b> [Source Code](https://github.com/Icinga/icinga2))) `GPL-2.0` `C++`
- 🌎 [LibreNMS](www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support. (<b><code>&nbsp;&nbsp;4617⭐</code></b> <b><code>&nbsp;&nbsp;2607🍴</code></b> [Source Code](https://github.com/librenms/librenms))) `GPL-3.0` `PHP`
- <b><code>&nbsp;10592⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [Linux Dash](https://github.com/afaqurk/linux-dash)) - A low-overhead monitoring web dashboard for a GNU/Linux machine. `MIT` `Nodejs/Go/Python/PHP`
- 🌎 [Monit](mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems.  🌎 [Source Code](bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
- 🌎 [Munin](munin-monitoring.org/) - Networked resource monitoring tool. (<b><code>&nbsp;&nbsp;2115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;481🍴</code></b> [Source Code](https://github.com/munin-monitoring/munin))) `GPL-2.0` `Perl/Shell`
- 🌎 [Naemon](www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features. (<b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/naemon/naemon-core))) `GPL-2.0` `C`
- 🌎 [Nagios](www.nagios.org/) - Computer system, network and infrastructure monitoring software application. (<b><code>&nbsp;&nbsp;1959⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [Source Code](https://github.com/NagiosEnterprises/nagioscore))) `GPL-2.0` `C`
- 🌎 [NetXMS](www.netxms.org/) - Open Source network and infrastructure monitoring and management. (<b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Source Code](https://github.com/netxms/netxms))) `LGPL-3.0/GPL-3.0` `Java/C++/C`
- [Observium Community Edition](http://www.observium.org/) - Network monitoring and management platform that provides real-time insight into network health and performance. `QPL-1.0` `PHP`
- 🌎 [openITCOCKPIT Community Edition](openitcockpit.io/) - Monitoring Suite featuring seamless integrations with Naemon, Checkmk, Grafana and more.  🌎 [Demo](demo.openitcockpit.io/), <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Source Code](https://github.com/openITCOCKPIT/openITCOCKPIT))) `GPL-3.0` `deb/Docker`
- [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework. (<b><code>&nbsp;&nbsp;1047⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [Source Code](https://github.com/performancecopilot/pcp))) `LGPL-2.1/GPL-2.0` `C`
- 🌎 [PHP Server Monitor](www.phpservermonitor.org/) - Open source tool to monitor your servers and websites. (<b><code>&nbsp;&nbsp;2194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;680🍴</code></b> [Source Code](https://github.com/phpservermon/phpservermon))) `GPL-3.0` `PHP`
- 🌎 [PhpSysInfo](phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely. (<b><code>&nbsp;&nbsp;1417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [Source Code](https://github.com/phpsysinfo/phpsysinfo))) `GPL-2.0` `PHP`
- 🌎 [Prometheus](prometheus.io/) - Service monitoring system and time series database. (<b><code>&nbsp;62989⭐</code></b> <b><code>&nbsp;10209🍴</code></b> [Source Code](https://github.com/prometheus/prometheus))) `Apache-2.0` `Go`
- 🌎 [Riemann](riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis. (<b><code>&nbsp;&nbsp;4264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;506🍴</code></b> [Source Code](https://github.com/riemann/riemann))) `EPL-1.0` `Java`
- <b><code>&nbsp;&nbsp;2191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [rtop](https://github.com/rapidloop/rtop)) - Interactive, remote system monitoring tool based on SSH. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [ruptime](https://github.com/alexmyczko/ruptime)) - Classic system status server. `AGPL-3.0` `Shell`
- <b><code>&nbsp;&nbsp;7450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Scrutiny](https://github.com/AnalogJ/scrutiny)) - Web UI for hard drive S.M.A.R.T monitoring, historical trends & real-world failure thresholds. `MIT` `Go`
- 🌎 [Sensu](sensu.io/) - Monitoring tool for ephemeral infrastructure and distributed applications. (<b><code>&nbsp;&nbsp;1095⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [Source Code](https://github.com/sensu/sensu-go))) `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Status](https://github.com/dani3l0/Status)) - Simple and lightweight system monitoring tool for small homeservers with a pleasant web interface.  🌎 [Demo](status.enshittification.social/) `MIT` `Python`
- 🌎 [Thruk](www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken. (<b><code>&nbsp;&nbsp;&nbsp;432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Source Code](https://github.com/sni/Thruk))) `GPL-1.0` `Perl`
- 🌎 [tirreno](www.tirreno.com/) - Application-level security to protect your app from threats, fraud, and abuse.  🌎 [Demo](play.tirreno.com/), <b><code>&nbsp;&nbsp;1121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Source Code](https://github.com/tirrenotechnologies/tirreno))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Uptime Kuma](uptime.kuma.pet/) - Modern, self-hosted monitoring tool with a clean UI and rich notification support. (<b><code>&nbsp;83440⭐</code></b> <b><code>&nbsp;&nbsp;7460🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma))) `MIT` `NodeJS`
- 🌎 [Wazuh](wazuh.com/) - Unified XDR and SIEM protection for endpoints and cloud workloads. (<b><code>&nbsp;14849⭐</code></b> <b><code>&nbsp;&nbsp;2170🍴</code></b> [Source Code](https://github.com/wazuh/wazuh))) `GPL-2.0` `C`
- 🌎 [Zabbix](www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.  🌎 [Source Code](git.zabbix.com/projects/ZBX/repos/zabbix/browse)) `GPL-2.0` `C`


### Network Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Network configuration management tools.

- 🌎 [GNS3](www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/GNS3/gns3-gui/))) `GPL-3.0` `Python`
- 🌎 [OpenWISP](openwisp.org/) - Open Source Network Management System for OpenWRT based routers and access points.  🌎 [Demo](openwisp.org/demo.html), [Source Code](https://github.com/openwisp)) `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;3290⭐</code></b> <b><code>&nbsp;&nbsp;1025🍴</code></b> [Oxidized](https://github.com/ytti/oxidized)) - Network device configuration backup tool. `Apache-2.0` `Ruby`
- 🌎 [phpIPAM](phpipam.net/) - Open source IP address management with PowerDNS integration. (<b><code>&nbsp;&nbsp;2692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;781🍴</code></b> [Source Code](https://github.com/phpipam/phpipam))) `GPL-3.0` `PHP`
- 🌎 [RANCID](www.shrubbery.net/rancid/) - Monitor network devices configuration and maintain history of changes. (<b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Source Code](https://github.com/haussli/rancid))) `BSD-3-Clause` `Perl/Shell`
- 🌎 [rConfig](www.rconfig.com/) - Network device configuration management tool. (<b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/rconfig/rconfig))) `GPL-3.0` `PHP`


### PaaS

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Platform-as-a-Service](en.wikipedia.org/wiki/Platform_as_a_service) software allows customers to provision, instantiate, run, and manage a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application. Also includes 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing) and 🌎 [Function-as-a-service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) software.


- 🌎 [CapRover](caprover.com/) - Build your own PaaS in a few minutes.  🌎 [Demo](captain.server.demo.caprover.com/#/login), <b><code>&nbsp;14880⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;964🍴</code></b> [Source Code](https://github.com/caprover/caprover))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [Coolify](coolify.io/) - An open-source & self-hostable Heroku / Netlify alternative (and even more). (<b><code>&nbsp;51224⭐</code></b> <b><code>&nbsp;&nbsp;3718🍴</code></b> [Source Code](https://github.com/coollabsio/coolify))) `Apache-2.0` `Docker`
- 🌎 [Dokku](dokku.com/) - An open-source PaaS (alternative to Heroku). (<b><code>&nbsp;31883⭐</code></b> <b><code>&nbsp;&nbsp;2021🍴</code></b> [Source Code](https://github.com/dokku/dokku))) `MIT` `Docker/Shell/Go/deb`
- <b><code>&nbsp;&nbsp;2229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [fx](https://github.com/metrue/fx)) - A tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`
- 🌎 [Kubero](www.kubero.dev/) - A self-hosted Heroku PaaS alternative for Kubernetes that implements GitOps.  🌎 [Demo](demo.kubero.dev/), <b><code>&nbsp;&nbsp;4161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Source Code](https://github.com/kubero-dev/kubero))) `GPL-3.0` `K8S/Nodejs/Go`
- 🌎 [LocalStack](localstack.cloud/) - LocalStack is a fully functional local AWS cloud stack. This includes Lambda for serverless computation. (<b><code>&nbsp;64521⭐</code></b> <b><code>&nbsp;&nbsp;4580🍴</code></b> [Source Code](https://github.com/localstack/localstack))) `Apache-2.0` `Python/Docker/K8S`
- 🌎 [Nhost](nhost.io/) - Firebase Alternative with GraphQL. Get a database and backend configured and ready in minutes. (<b><code>&nbsp;&nbsp;9089⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;561🍴</code></b> [Source Code](https://github.com/nhost/nhost))) `MIT` `Docker/Nodejs/Go`
- 🌎 [OpenFaaS](www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. (<b><code>&nbsp;26101⭐</code></b> <b><code>&nbsp;&nbsp;1969🍴</code></b> [Source Code](https://github.com/openfaas/faas))) `MIT` `Go`
- 🌎 [Tau](taubyte.com) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging. (<b><code>&nbsp;&nbsp;4975⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Source Code](https://github.com/taubyte/tau))) `BSD-3-Clause` `Go/Rust/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Trusted-CGI](https://github.com/reddec/trusted-cgi)) - Lightweight self-hosted lambda/applications/cgi/serverless-functions platform. `MIT` `Go/deb/Docker`


### Packaging

**[`^        back to top        ^`](#awesome-sysadmin)**

A 🌎 [package manager](en.wikipedia.org/wiki/Package_manager) or package-management system is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer in a consistent manner.

- 🌎 [aptly](www.aptly.info/) - Swiss army knife for Debian repository management. (<b><code>&nbsp;&nbsp;2776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [Source Code](https://github.com/aptly-dev/aptly))) `MIT` `Go`
- 🌎 [fpm](fpm.readthedocs.io/en/latest/) - Versatile multi format package creator. (<b><code>&nbsp;11439⭐</code></b> <b><code>&nbsp;&nbsp;1071🍴</code></b> [Source Code](https://github.com/jordansissel/fpm))) `MIT` `Ruby`
- <b><code>&nbsp;&nbsp;1309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [omnibus-ruby](https://github.com/chef/omnibus)) - Easily create full-stack installers for your project across a variety of platforms. `Apache-2.0` `Ruby`
- <b><code>&nbsp;&nbsp;&nbsp;399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [tito](https://github.com/dgoodwin/tito)) - Builds RPMs for git-based projects. `GPL-2.0` `Python`


### Project Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Web-based project management and bug tracking systems.

**Please visit 🌎 [awesome-selfhosted/Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**



### Queuing

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Message queues](en.wikipedia.org/wiki/Message_queue) and 🌎 [message broker](en.wikipedia.org/wiki/Message_broker) software, typically used for inter-process communication (IPC), or for inter-thread communication within the same process.

_See also: 🌎 [Cloud Native Landscape - Streaming & Messaging](landscape.cncf.io/?group=projects-and-products&view-mode=card#app-definition-and-development--streaming-messaging)_

- 🌎 [ActiveMQ](activemq.apache.org/) - Java message broker. (<b><code>&nbsp;&nbsp;2419⭐</code></b> <b><code>&nbsp;&nbsp;1484🍴</code></b> [Source Code](https://github.com/apache/activemq))) `Apache-2.0` `Java`
- 🌎 [BeanstalkD](beanstalkd.github.io/) - A simple, fast work queue. (<b><code>&nbsp;&nbsp;6692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;871🍴</code></b> [Source Code](https://github.com/beanstalkd/beanstalkd))) `MIT` `C`
- [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform. (<b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Source Code](https://github.com/gearman/gearmand))) `BSD-3-Clause` `C++`
- 🌎 [NSQ](nsq.io/) - A realtime distributed messaging platform. (<b><code>&nbsp;25884⭐</code></b> <b><code>&nbsp;&nbsp;2908🍴</code></b> [Source Code](https://github.com/nsqio/nsq))) `MPL-2.0` `Go`
- 🌎 [ZeroMQ](zeromq.org/) - Lightweight queuing system. ([Source Code](https://github.com/zeromq)) `GPL-3.0` `C++`


### Remote Desktop Clients

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Remote Desktop](en.wikipedia.org/wiki/Remote_desktop_software) client software.

_See also: 🌎 [awesome-selfhosted/Remote Access](awesome-selfhosted.net/tags/remote-access.html)_

- 🌎 [Remmina](www.remmina.org/) - Feature-rich remote desktop application for linux and other unixes.  🌎 [Source Code](gitlab.com/Remmina/Remmina)) `GPL-2.0` `C`
- 🌎 [Tiger VNC](tigervnc.org/) - High-performance, multi-platform VNC client and server. (<b><code>&nbsp;&nbsp;6905⭐</code></b> <b><code>&nbsp;&nbsp;1111🍴</code></b> [Source Code](https://github.com/TigerVNC/tigervnc))) `GPL-2.0` `C++`
- 🌎 [X2go](wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NoMachine/NX technology protocol.  🌎 [Source Code](code.x2go.org/gitweb)) `GPL-2.0` `Perl`


### Router

**[`^        back to top        ^`](#awesome-sysadmin)**

Software for management of [router](https://en.wikipedia.org/wiki/Router_(computing)) hardware.

- 🌎 [DD-WRT](dd-wrt.com/) - A Linux-based firmware for wireless routers and access points, originally designed for the Linksys WRT54G series.  🌎 [Source Code](svn.dd-wrt.com/)) `GPL-2.0` `C`
- 🌎 [IPFire](www.ipfire.org/) - Free network firewall distribution, based on the Linux operating system with easy-to-use web management console. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/ipfire/ipfire-2.x))) `GPL-2.0` `Shell/PHP/Other`
- 🌎 [OpenWrt](openwrt.org/) - A Linux-based router featuring Mesh networking, IPS via snort and AQM among many other features.  🌎 [Source Code](git.openwrt.org/openwrt/openwrt.git)) `GPL-2.0` `C`
- 🌎 [OPNsense](opnsense.org/) - An open source FreeBSD-based firewall and router with traffic shaping, load balancing, and virtual private network capabilities. ([Source Code](https://github.com/opnsense)) `BSD-2-Clause` `C/PHP`
- 🌎 [pfSense CE](www.pfsense.org/) - Free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. (<b><code>&nbsp;&nbsp;5551⭐</code></b> <b><code>&nbsp;&nbsp;1586🍴</code></b> [Source Code](https://github.com/pfsense/pfsense))) `Apache-2.0` `Shell/PHP/Other`


### Service Discovery

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Service discovery](en.wikipedia.org/wiki/Service_discovery) is the process of automatically detecting devices and services on a computer network.

- 🌎 [Consul](www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration. (<b><code>&nbsp;29762⭐</code></b> <b><code>&nbsp;&nbsp;4568🍴</code></b> [Source Code](https://github.com/hashicorp/consul))) `MPL-2.0` `Go`
- 🌎 [etcd](etcd.io/) - Distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery. (<b><code>&nbsp;51590⭐</code></b> <b><code>&nbsp;10327🍴</code></b> [Source Code](https://github.com/coreos/etcd))) `Apache-2.0` `Go`
- 🌎 [ZooKeeper](zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. (<b><code>&nbsp;12731⭐</code></b> <b><code>&nbsp;&nbsp;7335🍴</code></b> [Source Code](https://github.com/apache/zookeeper))) `Apache-2.0` `Java/C++`


### Software Containers

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Operating system–level](en.wikipedia.org/wiki/OS-level_virtualization) virtualization.

- 🌎 [Docker Compose](docs.docker.com/compose/) - Define and run multi-container Docker applications. (<b><code>&nbsp;37117⭐</code></b> <b><code>&nbsp;&nbsp;5725🍴</code></b> [Source Code](https://github.com/docker/compose))) `Apache-2.0` `Go`
- 🌎 [Docker Swarm](docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines. (<b><code>&nbsp;&nbsp;3587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;657🍴</code></b> [Source Code](https://github.com/moby/swarmkit))) `Apache-2.0` `Go`
- 🌎 [Docker](www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.  🌎 [Source Code](www.docker.com/community/open-source/)) `Apache-2.0` `Go`
- 🌎 [LXC](linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features. (<b><code>&nbsp;&nbsp;5117⭐</code></b> <b><code>&nbsp;&nbsp;1161🍴</code></b> [Source Code](https://github.com/lxc/lxc))) `GPL-2.0` `C`
- 🌎 [LXD](linuxcontainers.org/lxd/) - Container "hypervisor" and a better UX for LXC. (<b><code>&nbsp;&nbsp;4951⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [Source Code](https://github.com/lxc/lxd))) `Apache-2.0` `Go`
- 🌎 [OpenVZ](openvz.org) - Container-based virtualization for Linux.  🌎 [Source Code](src.openvz.org/projects/OVZ)) `GPL-2.0` `C`
- 🌎 [Podman](podman.io) - Daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode. Simply put: `alias docker=podman`. (<b><code>&nbsp;30851⭐</code></b> <b><code>&nbsp;&nbsp;2998🍴</code></b> [Source Code](https://github.com/containers/podman))) `Apache-2.0` `Go`
- 🌎 [Portainer Community Edition](www.portainer.io/) - Simple management UI for Docker. (<b><code>&nbsp;36716⭐</code></b> <b><code>&nbsp;&nbsp;2780🍴</code></b> [Source Code](https://github.com/portainer/portainer))) `Zlib` `Go`
- 🌎 [systemd-nspawn](www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - Lightweight, chroot-like, environment to run an OS or command directly under systemd. (<b><code>&nbsp;15363⭐</code></b> <b><code>&nbsp;&nbsp;4258🍴</code></b> [Source Code](https://github.com/systemd/systemd))) `GPL-2.0` `C`


### Status Pages

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Uptime](en.wikipedia.org/wiki/Uptime) is a measure of system reliability, expressed as the percentage of time a machine, typically a computer, has been working and available.

**Please visit 🌎 [awesome-selfhosted/Status / Uptime Pages](awesome-selfhosted.net/tags/status--uptime-pages.html)**



### Troubleshooting

**[`^        back to top        ^`](#awesome-sysadmin)**

Troubleshooting tools.

- 🌎 [grml](grml.org) - Bootable Debian Live CD with powerful CLI tools. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/grml/))) `GPL-3.0` `Shell`
- 🌎 [mitmproxy](mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems. (<b><code>&nbsp;42455⭐</code></b> <b><code>&nbsp;&nbsp;4469🍴</code></b> [Source Code](https://github.com/mitmproxy/mitmproxy))) `MIT` `Python`
- 🌎 [mtr](www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping. (<b><code>&nbsp;&nbsp;3145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;363🍴</code></b> [Source Code](https://github.com/traviscross/mtr))) `GPL-2.0` `C`
- 🌎 [Sysdig](www.sysdig.com/) - Capture system state and activity from a running Linux instance, then save, filter and analyze. (<b><code>&nbsp;&nbsp;8209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;752🍴</code></b> [Source Code](https://github.com/draios/sysdig))) `Apache-2.0` `Docker/Lua/C`
- 🌎 [Wireshark](www.wireshark.org/) - The world's foremost network protocol analyzer.  🌎 [Source Code](gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`


### Version control

**[`^        back to top        ^`](#awesome-sysadmin)**

Software versioning and revision control.

- 🌎 [Darcs](darcs.net/) - Cross-platform version control system, like git, mercurial or svn but with a very different approach: focus on changes rather than snapshots.  🌎 [Source Code](darcs.net/releases/)) `GPL-2.0` `Haskell`
- 🌎 [Fossil](www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.  🌎 [Source Code](www.fossil-scm.org/home/dir?ci=trunk)) `BSD-2-Clause` `C`
- 🌎 [Git](git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed. (<b><code>&nbsp;59412⭐</code></b> <b><code>&nbsp;27582🍴</code></b> [Source Code](https://github.com/git/git))) `GPL-2.0` `C`
- 🌎 [Mercurial](www.mercurial-scm.org/) - Distributed source control management tool.  🌎 [Source Code](repo.mercurial-scm.org/hg/file/tip)) `GPL-2.0` `Python/C/Rust`
- 🌎 [Subversion](subversion.apache.org/) - Client-server revision control system.  🌎 [Source Code](svn.apache.org/repos/asf/subversion/trunk/)) `Apache-2.0` `C`


### Virtualization

**[`^        back to top        ^`](#awesome-sysadmin)**

Virtualization software.

- 🌎 [Ganeti](www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen. (<b><code>&nbsp;&nbsp;&nbsp;565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Source Code](https://github.com/ganeti/ganeti))) `BSD-2-Clause` `Python/Haskell`
- 🌎 [KVM](www.linux-kvm.org) - Linux kernel virtualization infrastructure.  🌎 [Source Code](git.kernel.org/pub/scm/virt/kvm/kvm.git/)) `GPL-2.0/LGPL-2.0` `C`
- 🌎 [OpenNebula](opennebula.org/) - Build and manage enterprise clouds for virtualized services, containerized applications and serverless computing. (<b><code>&nbsp;&nbsp;1653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;520🍴</code></b> [Source Code](https://github.com/OpenNebula/one))) `Apache-2.0` `C++`
- 🌎 [oVirt](www.ovirt.org/) - Manages virtual machines, storage and virtual networks. ([Source Code](https://github.com/oVirt)) `Apache-2.0` `Java`
- 🌎 [Packer](www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration. (<b><code>&nbsp;15615⭐</code></b> <b><code>&nbsp;&nbsp;3323🍴</code></b> [Source Code](https://github.com/hashicorp/packer))) `MPL-2.0` `Go`
- 🌎 [Proxmox VE](www.proxmox.com/proxmox-ve) - Virtualization management solution.  🌎 [Source Code](git.proxmox.com/)) `GPL-2.0` `Perl/Shell`
- 🌎 [QEMU](www.qemu.org/) - QEMU is a generic machine emulator and virtualizer.  🌎 [Source Code](gitlab.com/qemu-project/qemu)) `LGPL-2.1` `C`
- 🌎 [Vagrant](www.vagrantup.com/) - Tool for building complete development environments. (<b><code>&nbsp;27219⭐</code></b> <b><code>&nbsp;&nbsp;4442🍴</code></b> [Source Code](https://github.com/hashicorp/vagrant))) `BUSL-1.1` `Ruby`
- 🌎 [VirtualBox](www.virtualbox.org/) - Virtualization product from Oracle Corporation.  🌎 [Source Code](www.virtualbox.org/browser/vbox)) `GPL-3.0/CDDL-1.0` `C++`
- 🌎 [XCP-ng](www.xcp-ng.org/) - Virtualization platform based on Xen Source and Citrix® Hypervisor (formerly XenServer). ([Source Code](https://github.com/xcp-ng)) `GPL-2.0` `C`
- 🌎 [Xen](www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.  🌎 [Source Code](xenbits.xenproject.org/gitweb/?p=xen.git;a=tree;hb=HEAD)) `GPL-2.0` `C`


### VPN

**[`^        back to top        ^`](#awesome-sysadmin)**

VPN software.

- 🌎 [DefGuard](defguard.net/) - True enterprise WireGuard with MFA/2FA and SSO. ([Source Code](https://github.com/DefGuard)) `Apache-2.0` `Rust`
- 🌎 [Dockovpn](dockovpn.io) - Out-of-the-box stateless dockerized OpenVPN server which starts in less than 2 seconds. (<b><code>&nbsp;&nbsp;1421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Source Code](https://github.com/dockovpn/dockovpn))) `GPL-2.0` `Docker`
- 🌎 [Firezone](www.firezone.dev/) - WireGuard based VPN Server and Firewall. (<b><code>&nbsp;&nbsp;8438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [Source Code](https://github.com/firezone/firezone))) `Apache-2.0` `Docker`
- <b><code>&nbsp;13224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;544🍴</code></b> [Gluetun VPN client](https://github.com/qdm12/gluetun)) -  VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.  `MIT` `docker`
- <b><code>&nbsp;35991⭐</code></b> <b><code>&nbsp;&nbsp;1934🍴</code></b> [Headscale](https://github.com/juanfont/headscale)) - Self-hostable fork of 🌎 [Tailscale](tailscale.com), cross-platform clients, simple to use, built-in (currently experimental) monitoring tools. `BSD-3-Clause` `Go`
- <b><code>&nbsp;17077⭐</code></b> <b><code>&nbsp;&nbsp;1109🍴</code></b> [Nebula](https://github.com/slackhq/nebula)) - A scalable p2p VPN with a focus on performance, simplicity and security. `MIT` `Go`
- 🌎 [ocserv](www.infradead.org/ocserv/) - Cisco AnyConnect-compatible VPN server.  🌎 [Source Code](gitlab.com/ocserv/ocserv)) `GPL-2.0` `C`
- 🌎 [OpenVPN](community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange. (<b><code>&nbsp;13292⭐</code></b> <b><code>&nbsp;&nbsp;3263🍴</code></b> [Source Code](https://github.com/OpenVPN/openvpn))) `GPL-2.0` `C`
- 🌎 [SoftEther](www.softether.org/) - Multi-protocol software VPN with advanced features. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/SoftEtherVPN/SoftEtherVPN/))) `Apache-2.0` `C`
- <b><code>&nbsp;13153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;787🍴</code></b> [sshuttle](https://github.com/sshuttle/sshuttle)) - Poor man's VPN. `LGPL-2.1` `Python`
- 🌎 [strongSwan](www.strongswan.org/) - Complete IPsec implementation for Linux. (<b><code>&nbsp;&nbsp;2782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [Source Code](https://github.com/strongswan/strongswan))) `GPL-2.0` `C`
- 🌎 [WireGuard](www.wireguard.com/) - Very fast VPN based on elliptic curve and public key crypto.  🌎 [Source Code](www.wireguard.com/repositories/)) `GPL-2.0` `C`


### Web

**[`^        back to top        ^`](#awesome-sysadmin)**
 🌎 [Web servers](en.wikipedia.org/wiki/Web_server) and 🌎 [reverse proxies](en.wikipedia.org/wiki/Reverse_proxy).

**Please visit 🌎 [awesome-selfhosted/Web Servers](awesome-selfhosted.net/tags/web-servers.html)**


--------------------

## List of Licenses

**[`^        back to top        ^`](#awesome-sysadmin)**

- `AGPL-3.0` - 🌎 [GNU Affero General Public License 3.0](spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - 🌎 [Apache, Version 2.0](spdx.org/licenses/Apache-2.0.html)
- `BSD-2-Clause` - 🌎 [BSD 2-clause "Simplified"](spdx.org/licenses/BSD-2-Clause.html)
- `BSD-3-Clause` - 🌎 [BSD 3-Clause "New" or "Revised"](spdx.org/licenses/BSD-3-Clause.html)
- `BUSL-1.1` - 🌎 [Business Source License 1.1](spdx.org/licenses/BUSL-1.1.html)
- `CC0-1.0` - 🌎 [Public Domain/Creative Common Zero 1.0](spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - 🌎 [Common Development and Distribution License 1.0](spdx.org/licenses/CDDL-1.0.html)
- `EPL-1.0` - 🌎 [Eclipse Public License 1.0](spdx.org/licenses/EPL-1.0.html)
- `GFDL-1.2` - 🌎 [GNU Free Documentation License 1.2](spdx.org/licenses/GFDL-1.2.html)
- `GPL-1.0` - 🌎 [GNU General Public License 1.0](spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - 🌎 [GNU General Public License 2.0](spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - 🌎 [GNU General Public License 3.0](spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - 🌎 [IBM Public License v1.0](spdx.org/licenses/IPL-1.0.html)
- `ISC` - 🌎 [ISC License](spdx.org/licenses/ISC.html)
- `LGPL-2.0` - 🌎 [GNU Lesser General Public License v2](spdx.org/licenses/LGPL-2.0.html)
- `LGPL-2.1` - 🌎 [GNU Lesser General Public License v2.1](spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - 🌎 [GNU Lesser General Public License v3](spdx.org/licenses/LGPL-3.0.html)
- `MIT` - 🌎 [MIT License](spdx.org/licenses/MIT.html)
- `MPL-2.0` - 🌎 [Mozilla Public License](spdx.org/licenses/MPL-2.0.html)
- `NLPL` - 🌎 [No Limit Public License](spdx.org/licenses/NLPL.html)
- `OLDAP-2.8` - 🌎 [Open LDAP Public License v2.8](spdx.org/licenses/OLDAP-2.8.html)
- `QPL-1.0` - 🌎 [Q Public License 1.0](spdx.org/licenses/QPL-1.0.html)
- `Vim` - 🌎 [Vim License](spdx.org/licenses/Vim.html)
- `Zlib` - 🌎 [zlib License](spdx.org/licenses/Zlib.html)


--------------------

## External links

## Communities / Forums

- 🌎 [ArsTechnica OpenForum](arstechnica.com/civis/) - IT Forum which is attached to a large news site.
- 🌎 [Reddit](www.reddit.com) - Really, really large bulletin board system.
  - 🌎 [/r/Linux](www.reddit.com/r/linux) - News and information about Linux.
  - 🌎 [/r/LinuxQuestions](www.reddit.com/r/linuxquestions)
  - 🌎 [/r/SysAdmin](www.reddit.com/r/sysadmin/)
- 🌎 [Spiceworks Community](community.spiceworks.com/start) - General enterprise IT news and small articles.
- 🌎 [StackExchange Network](stackexchange.com/sites#technology) - Q&A communities.
  - 🌎 [Server Fault](serverfault.com/) - StackExchange community for system and network administrators.

## Repositories

*Software package repositories.*

- 🌎 [AlternativeTo](alternativeto.net) - Find alternatives to software you know and discover new software.
- 🌎 [deb.sury.org](deb.sury.org/) - Repository with LAMP updated packages for Debian and Ubuntu.
- 🌎 [ElRepo](elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
- 🌎 [EPEL](fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
- 🌎 [IUS](ius.io/) - Community project that provides RPM packages for newer versions of select software for Enterprise Linux distributions.
- [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.
- 🌎 [Software Collections](www.softwarecollections.org) - Community Release of 🌎 [Red Hat Software Collections](access.redhat.com/documentation/en/red-hat-software-collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.

## Websites

- 🌎 [Cloud Native Software Landscape](landscape.cncf.io/?group=projects-and-products&view-mode=card) - Compilation of software and tools for cloud computing.
- 🌎 [ArchWiki](wiki.archlinux.org/) - Arch Linux Wiki which has really nice written articles valid for other distros.
- 🌎 [Gentoo Wiki](wiki.gentoo.org/) - Gentoo Linux Wiki with a lot in-detail description of Linux components.
- 🌎 [Awesome SysAdmin @ LibHunt](sysadmin.libhunt.com) - Your go-to SysAdmin Toolbox. Based on the list here.
- 🌎 [Ops School](www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
- 🌎 [Digital Ocean Tutorials](www.digitalocean.com/community/tutorials) - 6,000+ tutorials for getting the basics of certain applications/tools/systems administration topics.

------------------

## License

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license.

## Source
<b><code>&nbsp;33048⭐</code></b> <b><code>&nbsp;&nbsp;1937🍴</code></b> [awesome-foss/awesome-sysadmin](https://github.com/awesome-foss/awesome-sysadmin))