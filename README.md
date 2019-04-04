# NetEye 4 Community Portal

Welcome to the community repository for NetEye 4 users. 
This repository comes with the purpose to share the best-practices and enhancements created by our userbase. Started as initiative during the first projects, it provides now a platform to accelerate any implementation project by providing:
- how-to documentations for setup and configuration of a NetEye 4
- monitoring templates such as host- or service templates, commands and fields
- additionals monitoring plugins (scripts in part linked to 3rd party repositories)
- sample configurations to automate the configuration of best-practice configurations

## Gettings started guide for NetEye 4
This repo guides you thourgh the following steps of NetEye. Depending on the status of your NetEye 4 project it is suggested to go through both steps:
1. [setup of a fresh standalone NetEye 4](/doc/020_os_configuration.md)
2. integration and autosetup of templates, monitoring plugins and sample configurations

## References 
NetEye 3 configuration and templates collection. A limited NetEye 3 related [collection of enhancements can be found here](https://github.com/zampat/neteye3)

## Deployment of contents on NetEye

For the deployment of the provided contents, this repository provides scripts to replicate contents to the right paths on NetEye. In this case Monitoring Plugins are placed within the Plugins directory, Icinga 2 Agents within folders to support the deployment within your infrastructure. In the same moment mechanisms to verify if existing contents should be replaced are provided.

[Deployment of this contents can be automated by scripts documented in section "scripts"](scripts/).


## Contributing to this community project

[Read chapter 090_contributing_toGit.md](090_contributing_toGit.md)
