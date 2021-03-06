<p align="center">
  <img width="200" height="246" title="Ansible Logo" src="static/Ansible_logo.svg"><br>
  <b>Ansible Links</b><br>
</p>

---

Ansible Bookmarks.

## Learning
- [Ansible Get started](https://www.ansible.com/resources/get-started)
- [Ansible Introduction (Katacoda)](https://lab.redhat.com/ansible-introduction)
- [Ansible Automation Platform Workshops](https://ansible.github.io/workshops/)
- [Ansible Blog](https://www.ansible.com/blog)
- [Ansible Fest Atlanta 2019](https://www.ansible.com/resources/videos/ansiblefest-atlanta-2019)
- [Ansible Videos](https://www.ansible.com/resources/videos)
- [Ansible 101 - Standards](https://www.ansiblejunky.com/blog/ansible-101-standards/)
- [Good Practices for Ansible - GPA](https://github.com/redhat-cop/automation-good-practices)
- [The Bullhorn Newsletter](https://us19.campaign-archive.com/home/?u=56d874e027110e35dea0e03c1&id=d6635f5420)
- [Red Hat Ansible Automation Platform Product Status Update](https://www.ansible.com/blog/red-hat-ansible-automation-platform-product-status-update)
- [Red Hat Management Portfolio](https://github.com/ShaddGallegos/RHTI)

### Roles
- [Best Practices for Roles](https://github.com/oasis-roles/meta_standards)
- [Include vs Import](https://www.ansiblejunky.com/blog/ansible-101-include-vs-import/)

### Callback Modules
- [Reference for Ansible Callback Modules](https://github.com/sean-m-sullivan/callback_modules/blob/master/research.md)
- [Provisioning Callbacks](https://docs.ansible.com/ansible-tower/latest/html/userguide/job_templates.html#provisioning-callbacks)

### Inventory plugins
- [Using inventory plugins](https://docs.ansible.com/ansible/latest/plugins/inventory.html#using-inventory-plugins)
- [Inventory Plugin Examples](https://github.com/willtome/ansible-inventory)
- [AnsibleFest Presentation](https://www.ansible.com/managing-meaningful-inventories)

### Testing
- [Developing and Testing Ansible Roles with Molecule and Podman - Part 1](https://www.ansible.com/blog/developing-and-testing-ansible-roles-with-molecule-and-podman-part-1)

### Collections
- [Getting Started With Ansible Content Collections](https://www.ansible.com/blog/getting-started-with-ansible-collections)
- [Hands on with Ansible collections](https://www.ansible.com/blog/hands-on-with-ansible-collections)

#### Useful Collections
- [Tower Configuration](https://github.com/redhat-cop/tower_configuration)
- [Automation Hub Configuratio](https://github.com/redhat-cop/ah_configuration)

## Ansible Automation Platform

### Installing
- [Trial](https://www.redhat.com/en/technologies/management/ansible/try-it)
- [Red Hat Ansible Automation Platform - Red Hat Developer](https://developers.redhat.com/products/ansible/overview)
- [System Requirements](https://docs.ansible.com/ansible-tower/latest/html/installandreference/requirements_refguide.html)
- [Installing Ansible Automation Platform](https://docs.ansible.com/ansible-tower/latest/html/installandreference/tower_install_wizard.html)
- [Installer](https://releases.ansible.com/ansible-tower/setup/?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW)
- [Platform Life Cycle](https://access.redhat.com/support/policy/updates/ansible-tower)
- [Upgrading an Existing Tower Installation](https://docs.ansible.com/ansible-tower/latest/html/installandreference/upgrade_tower.html)
- [AWS Multi–AZ Ansible Tower Cluster](http://blog.domb.net/?p=2371)

#### AWX
- [Stop using alpha software and improve upgrades ](https://github.com/ansible/awx/issues/10166)

### Upstream projects
- [Ansible Core](https://github.com/ansible/ansible): a.k.a. Engine.
- [AWX](https://github.com/ansible/awx): Provides a web-based user interface, REST API, and task engine built on top of Ansible. It is the upstream project for Tower.
- [Ansible Navigator](https://github.com/ansible/ansible-navigator): A TUI for the Red Hat Ansible Automation Platform.
- [Ansible Runner](https://github.com/ansible/ansible-runner): Tower-> Runner-> Core.
- [Ansible Builder](https://github.com/ansible/ansible-builder): Automates the process of building execution environments.
- [Receptor](https://github.com/project-receptor/receptor): Overlay network intended to ease the distribution of work across a large and dispersed collection of workers.
- [Galaxy NG](https://github.com/ansible/galaxy_ng): Host your very own Ansible Galaxy server.
- [Automation Analytics Front End](https://github.com/RedHatInsights/tower-analytics-frontend)
- [Ansible Collections](https://github.com/ansible-collections): Great Ansible content.

### Architecture
- [Clustering](https://docs.ansible.com/ansible-tower/latest/html/administration/clustering.html#clustering): Clustering is sharing load between hosts. Each instance should be able to act as an entry point for UI and API access. This should enable Tower administrators to use load balancers in front of as many instances as they wish and maintain good data visibility.
- [Instance Groups](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#ag-instance-groups): . Instance groups can be assigned to one or more of; Organizations, Inventories, and Job Templates.
- [Ansible Tower container-based cluster running on OpenShift](https://docs.ansible.com/ansible-tower/latest/html/administration/openshift_configuration.html): Ansible Tower supports container-based clusters running on OpenShift.
- [Configure High Availability and/or Disaster Recovery on a Tower Cluster](https://github.com/redhat-cop/automate-tower-ha-dr#configure-high-availability-andor-disaster-recovery-on-a-tower-cluster): Toolkit not officially supported by Red Hat Ansible support/engineering and provided as is.
- [Security Best Practices](https://docs.ansible.com/ansible-tower/latest/html/administration/security_best_practices.html)
- [Ansible Automation Platform 1.2 - Reference Architecture](https://access.redhat.com/articles/6039601)

#### Container Groups
- [Container Groups docs](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#container-groups)
- [Ansible Tower Container Groups demo](https://www.youtube.com/watch?v=fBNTYOovtkI)
- [Introduction to Ansible Builder](https://www.ansible.com/blog/introduction-to-ansible-builder)

#### AAP Database
- [Red Hat Ansible Tower Database Scope of Coverage](https://access.redhat.com/articles/4010491)
- [Is Database Replication Supported with an Ansible Tower subscription?](https://access.redhat.com/solutions/3682951)

#### Considerations
- [Supported Platforms with Red Hat Ansible Automation Platform](https://access.redhat.com/articles/3168091): Platform Support Matrix for control nodes (the nodes that Ansible Engine is installed on) as well as the managed nodes (the nodes that Ansible Engine are connecting to and automating).
- [How are "managed nodes" defined as part of the Red Hat Ansible Automation Platform offering?](https://access.redhat.com/articles/3331481)

### RBAC and Authentication
- [Summary of Authentication Methods For Red Hat Ansible Tower](https://www.ansible.com/blog/summary-of-authentication-methods-in-red-hat-ansible-tower)
- [Setting up Enterprise Authentication](https://docs.ansible.com/ansible-tower/latest/html/administration/ent_auth.html#setting-up-enterprise-authentication)
- [Using two-factor SAML with Ansible Tower](https://www.ansible.com/blog/using-two-factor-saml-with-ansible-tower): 2FA to Ansible Tower with SAML, OAuth, and even some LDAP configs is fine. On the other hand, [2FA to managed machines is discouraged](https://access.redhat.com/solutions/3617131).
- [RBAC Guide and Recommendations](https://github.com/ShaddGallegos/RHTI/blob/master/Ansible_Tower/Ansible_PDF/Ansible_Tower-RBAC_Recommendations.pdf)
- [Organizations](https://docs.ansible.com/ansible-tower/latest/html/userguide/organizations.html): Logical collection of Users, Teams, Projects, and Inventories.
- [How To Configure SAML Authentication with Azure AD in Ansible Tower?](https://access.redhat.com/solutions/3889291)
- [Authenticating To Ansible Tower via Windows Active Directory](http://gregsowell.com/?p=6443)

### Internals
- [Ansible Tower 3.7.0 RabbitMQ Replacement](https://www.youtube.com/watch?v=smYgGswrDpc)

## Python
- [Python and Ansible to Automate a Network Security Workflow](https://medium.com/swlh/python-and-ansible-to-automate-a-network-security-workflow-28b9a44660c6)

## Network Automation
- [Red Hat Ansible Network Automation](https://www.ansible.com/products/network-automation)
- [Network MOP's as automated workflows](https://www.ansible.com/blog/network-mops-as-automated-workflows)
- [Using New Ansible Utilities for Operational State Management and Remediation](https://www.ansible.com/blog/using-new-ansible-utilities-for-operational-state-management-and-remediation)
- [Network automation instructional e-book](https://www.redhat.com/en/resources/network-automation-technical-e-book)
- [Network modules Ansible 2.9](https://docs.ansible.com/ansible/2.9/modules/list_of_network_modules.html)
- [Networking Project Board](https://github.com/orgs/ansible-collections/projects/3)
- [Red Hat Ansible Tower - Workshop and Demo](https://github.com/network-automation/tower_workshop)
- [Example of Networking Inventory with Ansible](https://github.com/network-automation/ansible_inventory_report)
- [How Do You Start Your Network Automation Adoption Journey?](https://www.landoman.com/2020/03/07/how-do-you-start-your-network-automation-adoption-journey/)
- [What networking platforms and versions are tested as part of Red Hat Ansible Network Automation?](https://access.redhat.com/articles/3185021)
- [Parsing semi-structured text with Ansible](https://docs.ansible.com/ansible/latest/network/user_guide/cli_parsing.html)
- [Jinja2 Template Designer for Automation](https://td4a.codethenetwork.com/)

### Network Resource Modules
- [Network Resource Modules](https://docs.ansible.com/ansible/latest/network/user_guide/network_resource_modules.html): From Ansible docs.
- [Network Features Coming Soon in Ansible Engine 2.9](https://www.ansible.com/blog/network-features-coming-soon-in-ansible-engine-2.9): Facts enhancements and **resource modules with scope of work**.
- [Ansible Network Resource Modules Quick Reference](https://www.ansible.com/hubfs/CY21%7C%20Ansible%20Network%20Automation%20Cheat%20Sheet.pdf)
- [Ansible Network Automation Feature Tracker](https://access.redhat.com/articles/5531421): Resource modules per vendor as November 2020.
- [Network:2021 Spring Roadmap](https://github.com/ansible/community/wiki/Network:2021-Spring-Roadmap#new-network-resource-modules): Latest network resource modules.
- [Deep dive on VLANS resource modules for network automation](https://www.ansible.com/blog/deep-dive-on-vlans-resource-modules-for-network-automation)
- [Getting Started With OSPFV2 Resource Modules](https://www.ansible.com/blog/getting-started-with-ospfv2-resource-modules)
- [Deep Dive: ACL Configuration Management Using Ansible Network Automation Resource Modules](https://www.ansible.com/blog/deep-dive-acl-configuration-management-using-ansible-network-automation-resource-modules)
- [Ansible Network Resource Modules: Deep Dive on Return Values](https://www.ansible.com/blog/ansible-network-resource-modules-deep-dive-on-return-values)
- [Ansible Network Resource Purge parameter](https://www.ansible.com/blog/ansible-network-resource-purge-parameter)

### Aruba
- [Aruba Switching for Data Center Networking (DCN)](https://github.com/aruba/aoscx-ansible-dcn-workflows)

### Cisco
- [Example of Cisco image upgrade with Ansible](https://github.com/colin-mccarthy/ansible_cisco_ios_upgrade)

### NetBox
- [Using NetBox for Ansible Source of Truth](https://www.ansible.com/blog/using-netbox-for-ansible-source-of-truth)

## Security
- [Simplify your security operations center](https://www.redhat.com/rhdc/managed-files/ma-security-automation-e-book-f24343-202007-en.pdf)
- [Security Automation with Ansible](https://www.ansible.com/hubfs/2018_Content/AnsibleAutomates-AnsibleForSecurityAutomation.pdf?hsLang=en-us)
- [Deploying OpenSCAP on Satellite using Ansible](https://www.redhat.com/en/blog/deploying-openscap-satellite-using-ansible)
- [PCI-DSS v3.2.1 Control Baseline for Red Hat Enterprise Linux 8](https://github.com/RedHatOfficial/ansible-role-rhel8-pci-dss)
- [DISA STIG for Red Hat Enterprise Linux 7](https://github.com/RedHatOfficial/ansible-role-rhel7-stig)
- [Implementing Proactive Security and Compliance Automation and DevSecOps](https://github.com/RedHatDemos/SecurityDemos/blob/master/2019Labs/ProactiveSecurityCompliance/documentation/README.adoc)
- [Workshop - Ansible Automation for Security Compliance](https://github.com/p-avery/ansible_compliance/tree/main/exercises)
- [ansible-hardening](https://github.com/openstack/ansible-hardening)
- [Ansible Lockdown](https://github.com/ansible/ansible-lockdown)
- [Red Hat Product Applicability Guide for PCI DSS version 3.2](https://www.redhat.com/rhdc/managed-files/cm-red-hat-product-applicability-guide-pci-dss-analyst-paper-f16584-201903-en.pdf)
- [STIG content for configuration management tools](https://public.cyber.mil/stigs/supplemental-automation-content/)
- [Ansible + OpenSCAP For Compliance Automation](https://medium.com/@jackprice/ansible-openscap-for-compliance-automation-14200fe70663)
- [Automating Security Compliance with Ansible: DevSecOps made Easy](https://madeintandem.com/blog/automating-security-compliance-ansible-devsecops-made-easy/)

## Service Now
- [Automating ServiceNow with Red Hat Ansible Automation Platform](https://www.ansible.com/blog/certified-collection-servicenow)
- [Opening and Closing Tickets](https://www.ansible.com/blog/ansible-servicenow-opening-and-closing-tickets)
- [Parsing facts from network devices using PyATS/Genie](https://www.ansible.com/blog/ansible-servicenow-part-2-parsing-facts-from-network-devices-using-pyats/genie)
- [Making outbound RESTful API calls to Red Hat Ansible Tower](https://www.ansible.com/blog/ansible-servicenow-howto-part-3-making-outbound-restful-api-calls-to-ansible-tower)
- [Connecting ServiceNow and Ansible Tower](https://github.com/shadowman-lab/Ansible-Config/tree/master/SNOW)
- [Governing Self-Service Cloud Provisioning](https://github.com/michaelford85/aws-deploy)
- [Ansible Service Now example](https://github.com/nleiva/ansible-snow)
- [Galaxy - Service Now](https://galaxy.ansible.com/servicenow/servicenow)

## Splunk
- [Centralize your Automation Logs with Ansible Tower and Splunk Enterprise](https://www.ansible.com/blog/centralize-your-automation-logs-with-ansible-tower-and-splunk-enterprise)

## Terraform
- [Ansible and HashiCorp: Better Together](https://www.hashicorp.com/resources/ansible-terraform-better-together)
- [HashiCorp Terraform and Red Hat Ansible Automation](https://www.redhat.com/en/resources/hashicorp-terraform-ansible-infrastructure-as-code-overview)
- [Ansible & Terraform – together or against?](https://www.opensourcerers.org/2020/10/12/ansible-and-terraform-integration/)
- [How To Use Ansible with Terraform for Configuration Management](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-with-terraform-for-configuration-management)
- [Red Hat and Hashicorp Demo Event](https://primetime.bluejeans.com/a2m/events/playback/e0c34c7f-3cae-4ddc-81ea-ee4d4cc7c91a)

## Kubernetes
- [How useful is Ansible in a Cloud-Native Kubernetes Environment?](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

## CMDB
- [Ansible Configuration Management Database](https://github.com/fboender/ansible-cmdb): Ansible-cmdb takes the output of Ansible's fact gathering and converts it into a static HTML overview page (and other things) containing system configuration information.
- [AnsibleDB](https://github.com/apidb-io/ansibledb_opensource): Gives you the ability to quickly collect facts about your Infrastucture estate [linux, windows & network devices] and via our API, pull out the information important to you.


## Miscellaneous
- [How to make the case for automation architecture: 5 ways to win investment](https://www.redhat.com/architect/automation-architecture): Shifting from personal automation to automation architecture is a systems challenge.
- [An IT executive's guide to automation](https://www.redhat.com/en/resources/executive-guide-to-automation-ebook): Learn the benefits of automation, how IT executives can ensure a successful rollout and adoption, and what to look for in an automation solution.
- [5 ways to process JSON data in Ansible](https://opensource.com/article/21/4/process-json-data-ansible)
- [Integrate your calendar with Ansible to avoid schedule conflicts](https://opensource.com/article/20/10/calendar-ansible): Make sure your automation workflow's schedule doesn't conflict with something else by integrating a calendar app into Ansible.
- [Create an Ansible module for integrating your Google Calendar](https://opensource.com/article/20/10/ansible-module-go): Learn how to write an Ansible module in Go to integrate Google Calendar into your automation workflow.
- [Install Ansible Tower on OpenShift 4.x on your Laptop](https://www.ansiblejunky.com/blog/ansible-tower-in-openshift-on-laptop/)

### My Ansible Content
- [grafana_agent](https://galaxy.ansible.com/nleiva/grafana_agent) (role)
- [capirca_acl](https://galaxy.ansible.com/nleiva/capirca_acl) (collection)
- [Networking examples](https://github.com/nleiva/ansible-networking) (playbooks)
- [Cloud Provisioning examples](https://github.com/nleiva/ansible-cloud) (playbooks)
- [Ansible Service Now example](https://github.com/nleiva/ansible-snow) (playbooks)
- [Store Ansible backup on AWS S3](https://github.com/nleiva/ansible-backup) (playbooks)
- [My Home Lab](https://github.com/nleiva/ansible-home) (playbooks)
