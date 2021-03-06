[English](README.md)

# Openstack Cheat Sheet

## 官方资源

* [主页](http://www.openstack.org/)
* [git源码地址](http://git.openstack.org/cgit)
* [Github源码镜像](https://github.com/openstack/openstack)
* [组件项目](http://governance.openstack.org/reference/projects/index.html) (Big Tent Governance)
* [官方文档](http://docs.openstack.org/)
* [邮件列表](http://lists.openstack.org/cgi-bin/mailman/listinfo)
* [IRC(freenode)](https://wiki.openstack.org/wiki/IRC)
* [Code review](https://review.openstack.org)
* [Roadmap](https://www.openstack.org/software/roadmap/)
* [Wiki](https://wiki.openstack.org/wiki/Main_Page)
* [Blueprints](https://blueprints.launchpad.net/openstack)
* [Bugs](https://bugs.launchpad.net/openstack)
* [支持公司](https://www.openstack.org/foundation/companies/) (Companies Supporting The OpenStack Foundation)
* [贡献统计(来源于stacklytics)](http://stackalytics.com/) (Provide transparent and meaningful statistics regarding contributions to both OpenStack itself and projects related to OpenStack.)
* [社区开发文档](http://docs.openstack.org/infra/manual/developers.html)(一步步教你如何加入社区开发)
* [代码提交测试](http://docs.openstack.org/infra/manual/sandbox.html#sandbox)(新手代码提交测试，新手可以通过此熟悉代码提交流程)
* [git commit message规范](https://wiki.openstack.org/wiki/GitCommitMessages#Summary_of_GIT_commit_message_structure)(提交代码时必须遵循的message的规范)
* [Openstack代码规范](http://docs.openstack.org/developer/hacking/#creating-unit-tests)(**Openstack代码规范，开发人员必读**)
* [Openstack各个组件的成熟度和热度统计](http://www.openstack.org/software/project-navigator)
* [Openstack版本列表](https://releases.openstack.org/)(可以查看数字版本对应Openstack版本代号，如Nova版本的13.x.x对应mitaka版本)


## 成员

### 白金会员

Provide a significant portion of the funding to achieve the Foundation's mission of protecting, empowering and promoting the OpenStack community and software. Each Platinum Member's company strategy aligns with the OpenStack mission and is responsible for committing full-time resources toward the project. There are **eight Platinum Members** at any given time, each of which holds a seat on the Board of Directors.

* [AT&T](http://www.att.com/)
* [Canonical](https://www.openstack.org/foundation/companies/profile/canonical)
* [Hewlett Packard Enterprise](https://www.openstack.org/foundation/companies/profile/hewlett-packard-enterprise)
* [IBM](https://www.openstack.org/foundation/companies/profile/ibm)
* [Intel](http://www.intel.cn/content/www/cn/zh/homepage.html)
* [Rackspace](https://www.openstack.org/foundation/companies/profile/rackspace)
* [Red Hat, Inc.](https://www.openstack.org/foundation/companies/profile/page-0)
* [SUSE](https://www.openstack.org/foundation/companies/profile/suse)

### 黄金会员

Provide funding and pledge strategic alignment to the OpenStack mission. There can be up to twenty-four Gold Members at any given time, subject to board approval. 

* [Aptira](https://aptira.com/)
* [CCAT](https://www.openstack.org/foundation/companies/profile/ccat)
* [Cisco](https://www.openstack.org/foundation/companies/profile/cisco)
* [Dell](https://www.openstack.org/foundation/companies/profile/dell)
* [DreamHost](https://www.openstack.org/foundation/companies/profile/dreamhost)
* [EasyStack](https://www.openstack.org/foundation/companies/profile/easystack)
* [EMC](http://www.emc.com/en-us/index.htm)
* [Ericsson](https://www.openstack.org/foundation/companies/profile/ericsson)
* [Fujitsu](https://www.openstack.org/foundation/companies/profile/fujitsu)
* [Hitachi](https://www.openstack.org/foundation/companies/profile/Hitachi-Data-Systems)
* [Huawei](https://www.openstack.org/foundation/companies/profile/huawei)
* [inwinSTACK](https://www.openstack.org/foundation/companies/profile/inwinstack)
* [Juniper Networks](https://www.openstack.org/foundation/companies/profile/juniper-networks)
* [Mirantis](https://www.openstack.org/foundation/companies/profile/mirantis)
* [NEC](https://www.openstack.org/foundation/companies/profile/nec)
* [NetApp](https://www.openstack.org/foundation/companies/profile/netapp)
* [Symantec](https://www.openstack.org/foundation/companies/profile/symantec-8)
* [UnitedStack Inc.](https://www.openstack.org/foundation/companies/profile/unitedstack)
* [Virtuozzo](https://www.openstack.org/foundation/companies/profile/virtuozzo)
* [Yahoo Inc.](https://www.openstack.org/foundation/companies/profile/yahoo)

## 自动化部署

* [Devstack](http://docs.openstack.org/developer/devstack/)(Oneiric powered development environment for openstack.)
* [Fuel](https://www.mirantis.com/products/mirantis-openstack-software/)(The leading purpose-built open source deployment and management tool for OpenStack.)
* [RDO](https://www.rdoproject.org/)(A communiaty of people using and deploying OpenStack on CentOS, Fedora, and Red Hat Enterprise Linux.)
* [openstack-puppet](https://wiki.openstack.org/wiki/Puppet)(Bring scalable and reliable IT automation to OpenStack cloud deployments using puppet.)
* [openstack-ansible](https://github.com/openstack/openstack-ansible)(Ansible playbooks for deploying OpenStack.)
* [kolla](https://github.com/openstack/kolla)(Deploying OpenStack using Docker.)
* [TripleO](https://wiki.openstack.org/wiki/TripleO)(A program aimed at installing, upgrading and operating OpenStack clouds using OpenStacks own cloud facilities as the foundations.)
* [SaltStack](https://github.com/cloudbase/salt-openstack)(Deploying Openstack using saltstack.)
* [packstack](https://github.com/openstack/packstack) (Install utility to deploy openstack on multiple hosts.)

## 监控

* [cloudpulse](https://github.com/openstack/cloudpulse): Openstack服务状态监控
* [Vitrage](https://github.com/openstack/Vitrage): Openstack故障分析, 故障生成树
* [fuel-plugin-external-zabbix](https://github.com/openstack/fuel-plugin-external-zabbix): Fuel Openstack zabbix监控项目,包含所有的监控项
* [fuel-ostf](https://github.com/openstack/fuel-ostf): Fuel的集成测试、功能测试框架


## 竞争对手

* [AWS](https://aws.amazon.com)(Offers reliable, scalable, and inexpensive cloud computing services.)
* [CloudStack](https://cloudstack.apache.org/)(Open source software designed to deploy and manage large networks of virtual machines, as highly scalable Infrastructure as a Service (IaaS) cloud computing platform.)
* [Vmware](http://www.vmware.com/)(The industry-leading virtualization software company.)
* [Docker](https://www.docker.com)(Docker containers and tooling make building and shipping applications dramatically easier and faster.)

## keystore

## glance

## nova

### Tips

列出所有的错误云主机:

```
nova list --status error --all-tenants
```

列出主机和映射的宿主机:

```
nova list --fields name,host
```

获取所有主机的id:

```
nova list --minimal | tail -n +4 | head -n -1 | cut -d ' ' -f 2
```

获取所有error状态的主机id:

```
nova list --minimal --status error --all-tenants | tail -n +4 | head -n -1 | cut -d ' ' -f 2
```

获取所有名称以"test"开头的主机:

```
nova list --name "^test"
```

获取所有主机挂载的volume id:

```
nova show --minimal 65e761b3-63b4-498f-9735-08e246c1e976 | grep 'os-extended-volumes:volumes_attached' | cut -d '|' -f 3 | jq '.[].id' | sed 's/"//g'
```

获取所有主机挂载的volume id以及设备名称:

```
nova show --minimal | grep 'os-extended-volumes:volumes_attached' | cut -d '|' -f 3 | jq '.[]|.id + " " + .device_name' | sed 's/"//g'
```


## cinder

获取所有error状态的实例:

```
cinder list --status error --all-tenants | tail -n +4 | head -n -1 | cut -d '|' -f 2
```

## neutron

## swift

## trove

## sahara

### 镜像列表

* [sahara-image-elements](https://github.com/openstack/sahara-image-elements)(Disk image elements for Sahara.)
* [prepared images](http://sahara-files.mirantis.com/images/upstream/).
* [Building Images for Vanilla Plugin](http://docs.openstack.org/developer/sahara/userdoc/vanilla_imagebuilder.html).
* [Building Images for Cloudera Plugin](http://docs.openstack.org/developer/sahara/userdoc/cdh_imagebuilder.html).

## manila

## magnum
