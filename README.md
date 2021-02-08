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
- [The Bullhorn Newsletter](https://us19.campaign-archive.com/home/?u=56d874e027110e35dea0e03c1&id=d6635f5420)
- [Red Hat Management Portfolio](https://github.com/ShaddGallegos/RHTI)

### Roles
- [Best Practices for Roles](https://github.com/oasis-roles/meta_standards)
- [Ansible 101 - Include vs Import](https://www.ansiblejunky.com/blog/ansible-101-include-vs-import/)

### Callback Modules
- [Reference for Ansible Callback Modules](https://github.com/sean-m-sullivan/callback_modules/blob/master/research.md)

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
- [Tower Configuration Collection](https://github.com/redhat-cop/tower_configuration)
- [Automation Hub Configuration Collection](https://github.com/redhat-cop/ah_configuration)

## Ansible Tower

### Installing
- [Red Hat Ansible Automation Platform Trial](https://www.redhat.com/en/technologies/management/ansible/try-it)
- [Ansible Tower installer](https://releases.ansible.com/ansible-tower/setup/?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW)
- [Red Hat Ansible Tower Life Cycle](https://access.redhat.com/support/policy/updates/ansible-tower)

### Architecture
- [Clustering](https://docs.ansible.com/ansible-tower/latest/html/administration/clustering.html#clustering): Clustering is sharing load between hosts. Each instance should be able to act as an entry point for UI and API access. This should enable Tower administrators to use load balancers in front of as many instances as they wish and maintain good data visibility.
- [Instance Groups](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#ag-instance-groups): . Instance groups can be assigned to one or more of; Organizations, Inventories, and Job Templates.
- [Ansible Tower container-based cluster running on OpenShift](https://docs.ansible.com/ansible-tower/latest/html/administration/openshift_configuration.html): Ansible Tower supports container-based clusters running on OpenShift.
- [Configure High Availability and/or Disaster Recovery on a Tower Cluster](https://github.com/redhat-cop/automate-tower-ha-dr#configure-high-availability-andor-disaster-recovery-on-a-tower-cluster): Toolkit not officially supported by Red Hat Ansible support/engineering and provided as is.
- [Security Best Practices](https://docs.ansible.com/ansible-tower/latest/html/administration/security_best_practices.html)

#### Container Groups
- [Container Groups docs](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#container-groups)
- [Ansible Tower Container Groups demo](https://www.youtube.com/watch?v=fBNTYOovtkI)
- [Introduction to Ansible Builder](https://www.ansible.com/blog/introduction-to-ansible-builder)

#### AAP Database
- [Red Hat Ansible Tower Database Scope of Coverage](https://access.redhat.com/articles/4010491)
- [Is Database Replication Supported with an Ansible Tower subscription?](https://access.redhat.com/solutions/3682951)

#### Considerations
- [Supported Platforms with Red Hat Ansible Engine](https://access.redhat.com/articles/3168091): Platform Support Matrix for control nodes (the nodes that Ansible Engine is installed on) as well as the managed nodes (the nodes that Ansible Engine are connecting to and automating).
- [How are "managed nodes" defined as part of the Red Hat Ansible Automation Platform offering?](https://access.redhat.com/articles/3331481)

### RBAC and Authentication
- [Summary of Authentication Methods For Red Hat Ansible Tower](https://www.ansible.com/blog/summary-of-authentication-methods-in-red-hat-ansible-tower)
- [Setting up Enterprise Authentication](https://docs.ansible.com/ansible-tower/latest/html/administration/ent_auth.html#setting-up-enterprise-authentication)
- [Using two-factor SAML with Ansible Tower](https://www.ansible.com/blog/using-two-factor-saml-with-ansible-tower): 2FA to Ansible Tower with SAML, OAuth, and even some LDAP configs is fine. On the other hand, [2FA to managed machines is discouraged](https://access.redhat.com/solutions/3617131).
- [RBAC Guide and Recommendations](https://github.com/ShaddGallegos/RHTI/blob/master/Ansible_Tower/Ansible_PDF/Ansible_Tower-RBAC_Recommendations.pdf)
- [Organizations](https://docs.ansible.com/ansible-tower/latest/html/userguide/organizations.html): Logical collection of Users, Teams, Projects, and Inventories.

### Internals
- [Ansible Tower 3.7.0 RabbitMQ Replacement](https://www.youtube.com/watch?v=smYgGswrDpc)

## Python
- [Python and Ansible to Automate a Network Security Workflow](https://medium.com/swlh/python-and-ansible-to-automate-a-network-security-workflow-28b9a44660c6)

## Network Automation
- [Red Hat Ansible Network Automation](https://www.ansible.com/products/network-automation)
- [Network Resource Modules](https://docs.ansible.com/ansible/latest/network/user_guide/network_resource_modules.html)
- [Network modules Ansible 2.9](https://docs.ansible.com/ansible/2.9/modules/list_of_network_modules.html)
- [Networking Project Board](https://github.com/orgs/ansible-collections/projects/3)
- [Red Hat Ansible Tower - Workshop and Demo](https://github.com/network-automation/tower_workshop)
- [Example of Networking Inventory with Ansible](https://github.com/network-automation/ansible_inventory_report)
- [Networking collection of Playbooks](https://github.com/nleiva/ansible-networking)
- [How Do You Start Your Network Automation Adoption Journey?](https://www.landoman.com/2020/03/07/how-do-you-start-your-network-automation-adoption-journey/)
- [Jinja2 Template Designer for Automation](https://td4a.codethenetwork.com/)

### The Inside Playbook
- [Network Features Coming Soon in Ansible Engine 2.9](https://www.ansible.com/blog/network-features-coming-soon-in-ansible-engine-2.9): Facts enhancements and **resource modules with scope of work**.
- [Deep dive on VLANS resource modules for network automation](https://www.ansible.com/blog/deep-dive-on-vlans-resource-modules-for-network-automation)
- [Getting Started With OSPFV2 Resource Modules](https://www.ansible.com/blog/getting-started-with-ospfv2-resource-modules)
- [Deep Dive: ACL Configuration Management Using Ansible Network Automation Resource Modules](https://www.ansible.com/blog/deep-dive-acl-configuration-management-using-ansible-network-automation-resource-modules)
- [Using NetBox for Ansible Source of Truth](https://www.ansible.com/blog/using-netbox-for-ansible-source-of-truth)
- [Ansible Network Resource Modules: Deep Dive on Return Values](https://www.ansible.com/blog/ansible-network-resource-modules-deep-dive-on-return-values)
- [Using New Ansible Utilities for Operational State Management and Remediation](https://www.ansible.com/blog/using-new-ansible-utilities-for-operational-state-management-and-remediation)

### Aruba
- [Aruba Switching for Data Center Networking (DCN)](https://github.com/aruba/aoscx-ansible-dcn-workflows)

### Cisco
- [Example of Cisco image upgrade with Ansible](https://github.com/colin-mccarthy/ansible_cisco_ios_upgrade)

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
- [Automating Security Compliance with Ansible: DevSecOps made Easy](https://madeintandem.com/blog/automating-security-compliance-ansible-devsecops-made-easy/)

## Service Now
- [Ansible + ServiceNow Part 1: Opening and Closing Tickets](https://www.ansible.com/blog/ansible-servicenow-opening-and-closing-tickets)
- [Ansible + ServiceNow Part 2: Parsing facts from network devices using PyATS/Genie](https://www.ansible.com/blog/ansible-servicenow-part-2-parsing-facts-from-network-devices-using-pyats/genie)
- [Ansible + ServiceNow Part 3: Making outbound RESTful API calls to Red Hat Ansible Tower](https://www.ansible.com/blog/ansible-servicenow-howto-part-3-making-outbound-restful-api-calls-to-ansible-tower)
- [Connecting ServiceNow and Ansible Tower](https://github.com/shadowman-lab/Ansible-Config/tree/master/SNOW)
- [Governing Self-Service Cloud Provisioning](https://github.com/michaelford85/aws-deploy)
- [Ansible Service Now example](https://github.com/nleiva/ansible-snow)
- [Galaxy - Service Now](https://galaxy.ansible.com/servicenow/servicenow)

## Miscellaneous
- [How to make the case for automation architecture: 5 ways to win investment](https://www.redhat.com/architect/automation-architecture): Shifting from personal automation to automation architecture is a systems challenge..
- [Integrate your calendar with Ansible to avoid schedule conflicts](https://opensource.com/article/20/10/calendar-ansible): Make sure your automation workflow's schedule doesn't conflict with something else by integrating a calendar app into Ansible.
- [Create an Ansible module for integrating your Google Calendar](https://opensource.com/article/20/10/ansible-module-go): Learn how to write an Ansible module in Go to integrate Google Calendar into your automation workflow.
- [Install Ansible Tower on OpenShift 4.x on your Laptop](https://www.ansiblejunky.com/blog/ansible-tower-in-openshift-on-laptop/)
