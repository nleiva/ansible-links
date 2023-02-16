<p align="center">
  <img width="200" height="246" title="Ansible Logo" src="static/Ansible_logo.svg"><br>
  <b>Ansible Links</b><br>
</p>

---

Curated list of Ansible resources online organized by topic.

## Learning
- [Get started with Red Hat Ansible Automation Platform](https://www.ansible.com/resources/get-started)
- [Get started with Ansible in three parts](https://developers.redhat.com/products/ansible/getting-started): Create, manage and scale by [Red Hat Developer](https://developers.redhat.com/).
- [DO007 - Ansible Basics: Automation Technical Overview (FREE)](https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview): Series of on-demand, online videos that introduce you to the Red Hat Ansible Automation Platform. Learn configuration management, provisioning, deploying, and managing compute infrastructure across cloud, virtual, and physical environments with Ansible.
- [Red Hat Ansible Automation Platform: A beginner’s guide](https://www.redhat.com/rhdc/managed-files/ma-intro-to-ansible-ebook-f31032-202204-en_0.pdf): Concise guide to Ansible Automation Platform, its benefits, and information to help you make the right decisions for your organization's automation practice.
- [Ansible Automation Platform Self-Paced Labs (Instruqt)](https://www.ansible.com/products/ansible-training): Hands-on learning scenarios provide you with a preconfigured Red Hat® Ansible® Automation Platform environment to experiment, practice, and see how automation can relieve you of manual tasks.
- [Ansible Self-Paced Labs (Community)](https://www.ansible.com/products/ansible-community-training): Interactive learning scenarios provide you with a pre-configured Ansible environment to experiment, learn, and see how Ansible can help you solve real-world problems. The environment runs entirely in your browser at your convenience, enabling you to learn more about our technology at your pace and time.
- [Ansible Automation Platform 2 Workshops](https://aap2.demoredhat.com/): The Red Hat Ansible Automation Workshops project is intended for effectively demonstrating Ansible’s capabilities through instructor-led workshops or self-paced exercises.
- [Official Ansible Product Demos](https://github.com/RedHatGov/product-demos#official-ansible-product-demos)
- [Ansible Blog](https://www.ansible.com/blog)
- [Ansible Fest](https://www.ansible.com/ansiblefest)
  - [Atlanta 2019](https://www.ansible.com/resources/videos/ansiblefest-atlanta-2019)
  - [Virtual 2020](https://www.youtube.com/watch?v=IXs46VEmBaY&list=PLdu06OJoEf2YcaRkIjvB7V35u6WI9yb19)
  - [Virtual 2021](https://www.youtube.com/watch?v=xVZM0QZtkeI&list=PLdu06OJoEf2aVagK5rW1uMA76H8rPw3CT)
  - [Chicago 2022](https://www.youtube.com/watch?v=GPYbxj5mi60&list=PLdu06OJoEf2aNRkQZQ8QM5ZwHc8QAoqtz)
- [Ansible Videos](https://www.ansible.com/resources/videos)

### Good Practices to write Ansible content
- [Ansible 101 - Standards](https://www.ansiblejunky.com/blog/ansible-101-standards/): By [John Wadleigh](https://github.com/ansiblejunky).
- [The Zen of Ansible](https://www.ansible.com/blog/the-zen-of-ansible): Based on [Timothy Appnel](https://github.com/tima)'s presentation at AnsibleFest 2022.
- [Good Practices for Ansible](https://github.com/redhat-cop/automation-good-practices#good-practices-for-ansible---gpa): This document aims to gather good practices from the field of Ansible practitioners at Red Hat, consultants, developers, and others. And thus it strives to give any Red Hat employee, partner or customer (or any Ansible user) a guideline from which to start in good conditions their automation journey.

## Ansible features
### Roles
- [Include vs Import](https://www.ansiblejunky.com/blog/ansible-101-include-vs-import/)

### Callback Modules
- [Reference for Ansible Callback Modules](https://github.com/sean-m-sullivan/callback_modules/blob/master/research.md)
- [Examples of the stdout or callback plugins](https://rndmh3ro.github.io/)
- [Provisioning Callbacks](https://docs.ansible.com/ansible-tower/latest/html/userguide/job_templates.html#provisioning-callbacks)

### Inventory plugins
- [Inventory Plugin Examples](https://github.com/willtome/ansible-inventory): by Will Tome.
- [Ansible Custom Inventory Plugin - a hands-on, quick start guide](https://termlen0.github.io/2019/11/16/observations/): by Ajay Chenampara.
- [JSON inventory plugin demo](https://github.com/nleiva/inventory): My JSON inventory plugin demo.
- [Using inventory plugins](https://docs.ansible.com/ansible/latest/plugins/inventory.html#using-inventory-plugins)
- [AnsibleFest Presentation](https://www.ansible.com/managing-meaningful-inventories)
- [Write your own Red Hat Ansible Tower inventory plugin](https://developers.redhat.com/blog/2021/03/10/write-your-own-red-hat-ansible-tower-inventory-plugin)
- [Developing an inventory plugin](https://docs.ansible.com/ansible/latest/dev_guide/developing_inventory.html#developing-an-inventory-plugin)
- [Ansible Constructed Inventory Plugin](https://cloudautomation.pharriso.co.uk/post/ansible-constructed-inventory-plugin/): by Pat Harrison.
- [Advanced Inventories Workshop](https://goetzrieger.github.io/ansible-tower-advanced/9-advanced-inventories/): by Goetz Rieger.

### Testing
- [Developing and Testing Ansible Roles with Molecule and Podman - Part 1](https://www.ansible.com/blog/developing-and-testing-ansible-roles-with-molecule-and-podman-part-1)

### Collections
- [Getting Started With Ansible Content Collections](https://www.ansible.com/blog/getting-started-with-ansible-collections)
- [Hands on with Ansible collections](https://www.ansible.com/blog/hands-on-with-ansible-collections)
- [Ansible Supported Collections, Versioning, and Release Strategy](https://access.redhat.com/articles/4993781)

#### Useful Collections
- [Tower Configuration](https://github.com/redhat-cop/tower_configuration)
- [Automation Hub Configuration](https://github.com/redhat-cop/ah_configuration)

## Red Hat Ansible Automation Platform

### Installation
- [Product trial](https://www.redhat.com/en/technologies/management/ansible/try-it): A single, 60-day, self-supported subscription to Red Hat® Ansible® Automation Platform for installation on Red Hat Enterprise Linux® (a subscription to Red Hat Enterprise Linux is included with this product trial, if not already installed).
- [Red Hat Ansible Automation Platform - Red Hat Developer](https://developers.redhat.com/products/ansible/overview): Download at no cost.
- [System Requirements](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.3/html/red_hat_ansible_automation_platform_planning_guide/platform-system-requirements): Red Hat Enterprise Linux 8.4 or later 64-bit (x86), Python 3.8 or later, PostgreSQL version 13. 16 GB RAM, 4 CPUs, 40 GB dedicated hard disk space (allocate a minimum of 20 GB to /var/lib/awx for execution environment storage).
- [Installing Red Hat Ansible Automation Platform](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.3/html/red_hat_ansible_automation_platform_installation_guide/assembly-platform-install-scenario): This guide helps you to understand the installation requirements and processes behind installing Ansible Automation Platform 2.3.
- [Red Hat Ansible Automation Platform Life Cycle](https://access.redhat.com/support/policy/updates/ansible-automation-platform)
- [What Ports Need To Be Opened In The Firewall For Ansible Automation Platform 2 Services?](https://access.redhat.com/solutions/6756251)
- [Deploying the Red Hat Ansible Automation Platform operator on OpenShift Container Platform](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.3/html/deploying_the_red_hat_ansible_automation_platform_operator_on_openshift_container_platform/index)
- [Upgrading an Existing Tower Installation](https://docs.ansible.com/ansible-tower/latest/html/installandreference/upgrade_tower.html)

### Ansible Automation Platform 2
- [Red Hat Ansible Automation Platform Product Status Update](https://www.ansible.com/blog/red-hat-ansible-automation-platform-product-status-update): Blog post update from Feb 2021.
- [Ansible Automation Platform 2.0 Early Access Homepage](https://access.redhat.com/articles/6145072): Most commonly used resources for Ansible Automation Platform 2 with all information, FAQ, links, etc.
- [Ansible Automation Platform 2.0 Release FAQ](https://access.redhat.com/articles/6192881): Product features or roadmap items as it relates to the Ansible Automation Platform (AAP) 2 Release.
- [What’s New in Ansible Automation Controller 4.0](https://access.redhat.com/articles/6184841): Why was Ansible Tower renamed to Automation controller?
- [Ansible Automation Platform 1.2 to 2 Migration Guide](https://access.redhat.com/documentation/en-us/reference_architectures/2022/html-single/ansible_automation_platform_1.2_to_2_migration_guide/index): Methodology to migrate from Ansible Automation Platform 1.2 to Ansible Automation Platform 2.
- [Migration from AAP 1.2 to Ansible Automation Platform 2: Side by side upgrade](https://www.youtube.com/watch?v=EKf3u1QdpNo&list=PLdu06OJoEf2YTVvHFPO6ZyZz5ax0FHe2L): Videos series with a step by step walkthrough of a side by side migration from AAP 1.2 to AAP 2 by [Julen Landa Alustiza](https://github.com/Zokormazo).

### Subscription
- [Certified Content](https://access.redhat.com/articles/3642632): Beginning with Ansible 2.9, the Ansible Content Collection subsystem was included as fully supported by Red Hat, and the certified content should be using this packaging format and distributed via Ansible Automation Hub.
- [What is included in Red Hat Ansible Automation Platform subscription?](https://access.redhat.com/articles/6057451): Self-Hosted and/or on-premises components; Automation controller, Private automation hub, Automation content navigator, Automation execution environments, Execution environment builder, Automation mesh, Ansible content tools, and Ansible Content Collections. Hosted Services on console.redhat.com; Red Hat Insights for Ansible Automation Platform, Automation hub, Automation services catalog.

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
- [Service Catalog API](https://github.com/RedHatInsights/catalog-api)
- [Service Catalog UI](https://github.com/RedHatInsights/catalog-ui)
- [Pinakes](https://github.com/ansible/pinakes): The upstream community project for RedHat's Automation Services Catalog product..
- [Drools](https://github.com/kiegroup/drools): Rule engine (Decision Manager).
- [Ansible Collections](https://github.com/ansible-collections): Great Ansible content.

### Architecture
- [Deploying Ansible Automation Platform 2.1](https://access.redhat.com/documentation/en-us/reference_architectures/2021/html-single/deploying_ansible_automation_platform_2.1/index): Best practices to deploy Ansible Automation Platform 2.1. Reference architecture that provides an opinionated setup of deploying a highly available Ansible Automation Platform environment.
- [Ansible Automation Platform 1.2 - Reference Architecture](https://access.redhat.com/articles/6039601)
- [Ansible Tower container-based cluster running on OpenShift](https://docs.ansible.com/ansible-tower/latest/html/administration/openshift_configuration.html): Ansible Tower supports container-based clusters running on OpenShift.
- [Security Best Practices](https://docs.ansible.com/ansible-tower/latest/html/administration/security_best_practices.html)

#### Backend Database
- [Red Hat Ansible Tower Database Scope of Coverage](https://access.redhat.com/articles/4010491)
- [Is Database Replication Supported with an Ansible Tower subscription?](https://access.redhat.com/solutions/3682951)

#### Container Groups
- [Container Groups docs](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#container-groups)
- [Instance Groups](https://docs.ansible.com/ansible-tower/latest/html/administration/external_execution_envs.html#ag-instance-groups): . Instance groups can be assigned to one or more of; Organizations, Inventories, and Job Templates.
- [Ansible Tower Container Groups demo](https://www.youtube.com/watch?v=fBNTYOovtkI)
- [Introduction to Ansible Builder](https://www.ansible.com/blog/introduction-to-ansible-builder)

#### High Availability
- [Configure High Availability and/or Disaster Recovery on a Tower Cluster](https://github.com/redhat-cop/automate-tower-ha-dr#configure-high-availability-andor-disaster-recovery-on-a-tower-cluster): Toolkit not officially supported by Red Hat Ansible support/engineering and provided as is.
- [AWX Clustering/HA Overview](https://github.com/ansible/awx/blob/15964dc3959472950db23ed6463c7f4e1978192c/docs/clustering.md#awx-clusteringha-overview): Allow grouping of clustered instances into different pools/queues.
- [Manage automation controller active and passive multisite architecture with Ansible](https://www.redhat.com/architect/automation-controller-active-passive-architecture-cac): Create a workflow to achieve consistency across multiple Ansible Automation Platform sites simultaneously. Remove the overhead associated with maintaining database backups or expensive replication solutions while enabling disaster recovery and failover. 
- [Clustering](https://docs.ansible.com/ansible-tower/latest/html/administration/clustering.html#clustering): Clustering is sharing load between hosts. Each instance should be able to act as an entry point for UI and API access. This should enable Tower administrators to use load balancers in front of as many instances as they wish and maintain good data visibility.
- [AWS Multi–AZ Ansible Tower Cluster](http://blog.domb.net/?p=2371)

#### Platform as Code
- [Automation controller workflow deployment as code](https://www.ansible.com/blog/automation-controller-workflow-deployment-as-code): A programmatic way to create, update or delete automation controller objects as well as perform tasks such as run jobs, change configurations and much more.
- [Creating an Ansible controller config as code pipeline](https://www.redhat.com/en/blog/creating-ansible-controller-config-code-pipeline): Create an organization-wide solution to deploying configuration as code.
- [Ansible Automation Platform 2.3 Configuration as Code Improvements](https://www.ansible.com/blog/ansible-automation-platform-2.3-configuration-as-code-improvements): What Configuration as Code (CaC) is and the benefits it can bring to your organization, including a UI and API walkthrough of automation controller and how to take a full Configuration as Code approach to your automation infrastructure.
- [Manage automation controller Configuration as Code (CaC) with Ansible](https://www.redhat.com/architect/ansible-automation-controller-cac-gitops): An alternative to database replication to copy data from one environment to another.

#### Considerations
- [Supported Platforms with Red Hat Ansible Automation Platform](https://access.redhat.com/articles/3168091): Platform Support Matrix for control nodes (the nodes that Ansible Engine is installed on) as well as the managed nodes (the nodes that Ansible Engine are connecting to and automating).
- [How are "managed nodes" defined as part of the Red Hat Ansible Automation Platform offering?](https://access.redhat.com/articles/3331481)

### RBAC and Authentication
- [Summary of Authentication Methods For Red Hat Ansible Tower](https://www.ansible.com/blog/summary-of-authentication-methods-in-red-hat-ansible-tower)
- [Setting up Enterprise Authentication](https://docs.ansible.com/ansible-tower/latest/html/administration/ent_auth.html#setting-up-enterprise-authentication)
- [Using two-factor SAML with Ansible Tower](https://www.ansible.com/blog/using-two-factor-saml-with-ansible-tower): 2FA to Ansible Tower with SAML, OAuth, and even some LDAP configs is fine. On the other hand, [2FA to managed machines is discouraged](https://access.redhat.com/solutions/3617131).
- [Mapping SAML attributes to Red Hat Ansible Automation Platform organizations and teams](https://www.ansible.com/blog/mapping-saml-attributes-to-red-hat-ansible-automation-platform-organizations-and-teams)
- [RBAC Guide and Recommendations](https://github.com/ShaddGallegos/RHTI/blob/master/Ansible_Tower/Ansible_PDF/Ansible_Tower-RBAC_Recommendations.pdf)
- [Organizations](https://docs.ansible.com/ansible-tower/latest/html/userguide/organizations.html): Logical collection of Users, Teams, Projects, and Inventories.
- [How To Configure SAML Authentication with Azure AD in Ansible Tower?](https://access.redhat.com/solutions/3889291)
- [Authenticating To Ansible Tower via Windows Active Directory](http://gregsowell.com/?p=6443)

### Internals
- [Ansible Tower 3.7.0 RabbitMQ Replacement](https://www.youtube.com/watch?v=smYgGswrDpc)

## Python
- [Python and Ansible to Automate a Network Security Workflow](https://medium.com/swlh/python-and-ansible-to-automate-a-network-security-workflow-28b9a44660c6)

## Go
- [Get Yourself GOing with Ansible](https://codeburst.io/get-yourself-going-with-ansible-60ca623bf4)

## Network Automation
- [Ansible Network Automation](https://www.ansible.com/products/network-automation): Red Hat Ansible Network Automation main page.
- [Red Hat's Network Automation guide](https://www.redhat.com/rhdc/managed-files/ma-network-automation-guide-ebook-f32023-202209-en.pdf): Goes from assessing your network automation maturity to top network automation use cases.
- [Network MOP's as automated workflows](https://www.ansible.com/blog/network-mops-as-automated-workflows): A good way to translate network automation into business value is by taking existing processes and automating them to make them more consistent and faster to run. 
- [Network automation: What architects need to know](https://www.redhat.com/architect/network-automation): Network automation is a marathon, so you might want to begin with baby steps. You also need clear business metrics and to understand how to measure them for success to help others see the path forward.
- [Five great use cases for Ansible Network Automation](https://www.youtube.com/watch?v=wXUgYfZKMHU&list=PLdu06OJoEf2axRLJvwAbAIWUOhPEv_emX): Presented by [Sean Cavanaugh](https://github.com/IPvSean), Technical Marketing Manager at Red Hat.
- [Network automation instructional e-book](https://www.redhat.com/en/resources/network-automation-technical-e-book): Technical guide to implementing common network automation tasks with Red Hat® Ansible® Automation Platform.
- [Using network automation to power modern applications](https://www.redhat.com/en/engage/growing-network-automation-s-202111230714): [Mike Fratto](https://451research.com/analyst-team/analyst/Mike+Fratto) at 451 Research explores how network automation differs from automated network management and which features to consider as you mature your network automation solution.
- [How Do You Start Your Network Automation Adoption Journey?](https://www.landoman.com/2020/03/07/how-do-you-start-your-network-automation-adoption-journey/): One of the best ways for people to begin managing their network in a practical way by Landon Holley.
- [Infrastructure Awareness - Technical Demo](https://www.youtube.com/watch?v=2O-f7PnxA3A): Retrieve facts from network devices and build dynamic documentation to help network engineers and architects gather automated information about their network. By [Sean Cavanaugh](https://github.com/IPvSean).
- [Using New Ansible Utilities for Operational State Management and Remediation](https://www.ansible.com/blog/using-new-ansible-utilities-for-operational-state-management-and-remediation): Comparing the current operational state of your IT infrastructure to your desired state.
- [Ansible Network: Workshop - Network Tool Kit](https://github.com/network-automation/toolkit): By [Sean Cavanaugh](https://github.com/IPvSean).
- [Ansible Network Roadmap](https://github.com/ansible/community/wiki/Network:-CY22-Q3-Q4,-CY23-Roadmap): By [Trishna Guha](https://github.com/trishnaguha).
- [Ansible Network: Project Board](https://github.com/orgs/ansible-collections/projects/3): Ansible Networking Collection Project Board.
- [What networking platforms and versions are tested as part of Red Hat Ansible Network Automation?](https://access.redhat.com/articles/3185021)

### Working with Network Configurations
- [Network Tool Kit](https://github.com/network-automation/toolkit): Collection of network roles used for the Ansible Network Automation Workshop.
- [Parsing semi-structured text with Ansible](https://docs.ansible.com/ansible/latest/network/user_guide/cli_parsing.html): Documentation of the cli_parse module that parses semi-structured data such as network configurations into structured data to allow programmatic use of the data from that device.
- [Ansible Module for utilizing Hierarchical Configuration](https://github.com/netdevops/hconfig-remediation-ansible): Hierarchical Configuration takes a running configuration of a network device, compares it to its intended configuration, and builds the remediation steps necessary to bring a device into spec with its intended configuration.
- [Jinja2 Template Designer for Automation](https://td4a.codethenetwork.com/): To test online your jinja2 template.

### Network Inventory
- [Network Inventory Report with Ansible](https://github.com/AdamMack2007/ansible_inventory_report#network-inventory-report-with-ansible): Creates a compliance report for network devices. By [Adam Mack](https://github.com/AdamMack2007).
- [Example of Networking Inventory with Ansible](https://github.com/network-automation/ansible_inventory_report): Generate a HTML report using the template module from facts gathered with the nxos_facts module. By [Sean Cavanaugh](https://github.com/IPvSean).
- [Git as a source of truth for network automation](https://vincent.bernat.ch/en/blog/2021-source-of-truth-network)
- [Network CVE Report with Ansible](https://adammack2007.github.io/Ansible-Cisco-CVE-Parser/): Creates a report of all CVEs that affect a specific platform (Cisco NXOS, IOS, IOS-XE) based on the version of the software the hosts are running. By [Adam Mack](https://github.com/AdamMack2007).

### Network Resource Modules
- [What is a resource module](https://github.com/ansible-community/community-topics/issues/33#issuecomment-897029700)
- [Network Resource Modules](https://docs.ansible.com/ansible/latest/network/user_guide/network_resource_modules.html): From Ansible docs.
- [Network Features Coming Soon in Ansible Engine 2.9](https://www.ansible.com/blog/network-features-coming-soon-in-ansible-engine-2.9): Facts enhancements and **resource modules with scope of work**.
- [Ansible Network Resource Modules Quick Reference](https://www.ansible.com/hubfs/CY21%7C%20Ansible%20Network%20Automation%20Cheat%20Sheet.pdf)
- [Network Resource Module Models](https://github.com/ansible-network/resource_module_models/tree/master/models)
- [Ansible Network Automation Feature Tracker](https://access.redhat.com/articles/5531421): Resource modules per vendor as November 2020.
- [Network:2021 Spring Roadmap](https://github.com/ansible/community/wiki/Network:2021-Spring-Roadmap#new-network-resource-modules): Latest network resource modules.
- [Deep dive on VLANS resource modules for network automation](https://www.ansible.com/blog/deep-dive-on-vlans-resource-modules-for-network-automation)
- [Getting Started With OSPFV2 Resource Modules](https://www.ansible.com/blog/getting-started-with-ospfv2-resource-modules)
- [Deep Dive: ACL Configuration Management Using Ansible Network Automation Resource Modules](https://www.ansible.com/blog/deep-dive-acl-configuration-management-using-ansible-network-automation-resource-modules)
- [Ansible Network Resource Modules: Deep Dive on Return Values](https://www.ansible.com/blog/ansible-network-resource-modules-deep-dive-on-return-values)
- [Ansible Network Resource Purge parameter](https://www.ansible.com/blog/ansible-network-resource-purge-parameter)

### Arista
- [Ansible Network Automation with Arista CloudVision and Arista Validated Designs](https://www.ansible.com/resources/webinars-training/ansible-network-automation-with-arista-cloudvision-and-arista): Live Demo of Network services provisioning and workflow with Ansible and CloudVision and deep-dive into the “stackable template architecture” by Brad Thornton.
- [Ansible Collection For Arista Validated Designs](https://github.com/aristanetworks/ansible-avd#ansible-collection-for-arista-validated-designs---aristaavd)
- [Ansible Modules for Arista CloudVision Platform](https://github.com/aristanetworks/ansible-cvp)
- [Addressing NetOps issues with Event-Driven Ansible](https://www.ansible.com/blog/addressing-netops-issues-with-event-driven-ansible): Respond to events we gather from things like network telemetry.
- [gNMI and NATS Demo](https://github.com/arista-netdevops-community/Ansible-Event-Driven-Automation-Examples/tree/main/nats#nats-demo).

### Aruba
- [Aruba Switching for Data Center Networking (DCN)](https://github.com/aruba/aoscx-ansible-dcn-workflows)

### Cisco
- [Cisco with Ansible](https://developer.cisco.com/automation-ansible/): DevNet tutorials to start your automation journey with Ansible.
- [Simplifying network automation with Red Hat Ansible and Cisco](https://www.youtube.com/watch?v=tYKHP-3ol9c): Simplify, optimize, and automate network operations.  Automation gives you the agility, flexibility, and consistency you need to keep infrastructure running at peal performance.
- [Example of Cisco image upgrade with Ansible](https://github.com/colin-mccarthy/ansible_cisco_ios_upgrade).
- [Ansible Network Automation - Config Backup and Restore](https://www.youtube.com/watch?v=dfRzfkbmx-A): Configuration backup and restore for a Cisco IOS-XE network router demo by [Sean Cavanaugh](https://github.com/IPvSean).
- [Automate Cisco ACI Tenant Profile Creation](https://github.com/CiscoSE/ACI_Ansible_FastStrike): Parse a CSV file that includes the needed attributes to automate and orchestrate creation of new tenants.
- [Red Hat Fireside Chat with WWT and Cisco](https://www.youtube.com/watch?v=6Ypxh0fUo1Y): Red Hat guests from Cisco Systems and World Wide Technology (WWT) shared their experiences on how partnerships have benefited customers who are implementing next generation network automation.

### F5
- [Deploy production grade automation technology at scale with Red Hat and F5](https://www.redhat.com/rhdc/managed-files/pa-network-automation-for-everyone-f5-e-book-f32193-202211-en.pdf): F5 provides Certified Content Collections for both physical and virtual editions of BIG-IP, allowing you to automate networks of any size more simply. You can automate and orchestrate nearly all Day 0 to Day 2 tasks over a wide range of use cases. A dedicated staff builds and regularly maintains these integrations, ensuring that they are always up to date and reliable for production use.
- [Ansible F5 Networking Workshop](https://aap2.demoredhat.com/exercises/ansible_f5/)

### Juniper
- [Understanding the Ansible for Junos OS Collections, Roles, and Modules](https://www.juniper.net/documentation/us/en/software/junos-ansible/ansible/topics/concept/junos-ansible-modules-overview.html)

### NetBox
- [Using NetBox for Ansible Source of Truth](https://www.ansible.com/blog/using-netbox-for-ansible-source-of-truth)

### Palo Alto
- [Palo Alto Ansible LIVEcommunity](https://live.paloaltonetworks.com/t5/ansible/ct-p/Ansible)
- [Module reference](https://paloaltonetworks.github.io/pan-os-ansible/modules.html)
- [Palo Alto Networks playbook examples](https://github.com/PaloAltoNetworks/ansible-playbooks)
- [Michael Ford's examples](https://github.com/michaelford85/ansible-panos)

## Security
- [Simplify your security operations center](https://www.redhat.com/rhdc/managed-files/ma-security-automation-e-book-f24343-202007-en.pdf)
- [Security Automation with Ansible](https://www.ansible.com/hubfs/2018_Content/AnsibleAutomates-AnsibleForSecurityAutomation.pdf?hsLang=en-us)
- [Deploying OpenSCAP on Satellite using Ansible](https://www.redhat.com/en/blog/deploying-openscap-satellite-using-ansible)
- [Ansible for Red Hat Enterprise Linux Security Automation](https://github.com/raedrizk/ansible-security-workshop): 90-minute workshop with day-to-day security operations hands-on exercises by [Raed Soliman](https://github.com/raedrizk).
- [Implementing Proactive Security and Compliance Automation and DevSecOps](https://github.com/RedHatDemos/SecurityDemos/blob/master/2019Labs/ProactiveSecurityCompliance/documentation/README.adoc)
- [Workshop - Ansible Automation for Security Compliance](https://github.com/p-avery/ansible_compliance/tree/main/exercises)
- [ansible-hardening](https://github.com/openstack/ansible-hardening)
- [Ansible Lockdown](https://github.com/ansible/ansible-lockdown)
- [STIG content for configuration management tools](https://public.cyber.mil/stigs/supplemental-automation-content/)
- [Ansible + OpenSCAP For Compliance Automation](https://medium.com/@jackprice/ansible-openscap-for-compliance-automation-14200fe70663)
- [Enterprise Compliance and Security with Ansible (Ansible Automates)](https://www.ansible.com/videos-ansible-automates-enterprise-compliance-and-security-with-ansible)
- [Automating Security Compliance with Ansible: DevSecOps made Easy](https://madeintandem.com/blog/automating-security-compliance-ansible-devsecops-made-easy/)
- [ComplianceAsCode](https://github.com/ComplianceAsCode/content#ansible): Ansible playbooks generated from security profiles.
### RHEL
- [Implementing Content for Automated Security Compliance to Custom Policies (Workshop)](https://2020-summit-labs.gitlab.io/rhel-custom-security-content/)
- [PCI-DSS v3.2.1 Control Baseline for Red Hat Enterprise Linux 8](https://github.com/RedHatOfficial/ansible-role-rhel8-pci-dss): Ensures PCI-DSS v3.2.1 security configuration settings are applied.
- [CIS Red Hat Enterprise Linux 8 Benchmark for Level 2 - Server](https://github.com/RedHatOfficial/ansible-role-rhel8-cis): This profile defines a baseline that aligns to the "Level 2 - Server" configuration from the Center for Internet Security® Red Hat Enterprise Linux 8 Benchmark™, v1.0.1, released 2021-05-19.
- [DISA STIG for Red Hat Enterprise Linux 7](https://github.com/RedHatOfficial/ansible-role-rhel7-stig): This profile contains configuration checks that align to the DISA STIG for Red Hat Enterprise Linux V3R4.
- [Red Hat Product Applicability Guide for PCI DSS version 3.2](https://www.redhat.com/rhdc/managed-files/cm-red-hat-product-applicability-guide-pci-dss-analyst-paper-f16584-201903-en.pdf)

## Service Now
- [Introducing the Ansible API for ServiceNow ITSM](https://www.ansible.com/blog/introducing-the-ansible-api-for-servicenow-itsm): A result of the release of Rome, but it's also compatible with ServiceNow ITSM San Diego and Tokyo.
- [Automating ServiceNow with Red Hat Ansible Automation Platform](https://www.ansible.com/blog/certified-collection-servicenow)
- [Opening and Closing Tickets](https://www.ansible.com/blog/ansible-servicenow-opening-and-closing-tickets)
- [Ansible + ServiceNow Demos](https://aap2.demoredhat.com/demos/servicenow/): These demos are intended for effectively demonstrating Ansible + ServiceNow capabilities with prescriptive guides on the Ansible Automation Workshop infrastructure.
- [Parsing facts from network devices using PyATS/Genie](https://www.ansible.com/blog/ansible-servicenow-part-2-parsing-facts-from-network-devices-using-pyats/genie)
- [Making outbound RESTful API calls to Red Hat Ansible Tower](https://www.ansible.com/blog/ansible-servicenow-howto-part-3-making-outbound-restful-api-calls-to-ansible-tower)
- [Connecting ServiceNow and Ansible Tower](https://github.com/shadowman-lab/Ansible-Config/tree/master/SNOW)
- [Governing Self-Service Cloud Provisioning](https://github.com/michaelford85/aws-deploy)
- [Ansible Service Now example](https://github.com/nleiva/ansible-snow)
- [Galaxy - Service Now](https://galaxy.ansible.com/servicenow/servicenow)

## Splunk
- [Centralize your Automation Logs with Ansible Tower and Splunk Enterprise](https://www.ansible.com/blog/centralize-your-automation-logs-with-ansible-tower-and-splunk-enterprise)
- [Splunk-Ansible documentation](https://splunk.github.io/splunk-ansible/): Collection of Splunk configuration best practices, written as Ansible playbooks for configuring Splunk Enterprise and Universal Forwarder instances based on a declarative configuration. The playbooks are internally-vetted procedures and operations that administer and manage Splunk as done within the company.

## Terraform
- [Ansible vs. Terraform Demystified](https://www.ansible.com/blog/ansible-vs.-terraform-demystified): The two tools are better together and can work in harmony to create a better experience for developers and operations teams. By [Sean Cavanaugh](https://github.com/IPvSean).
- [Ansible and HashiCorp: Better Together](https://www.hashicorp.com/resources/ansible-terraform-better-together): Presenters from Red Hat and HashiCorp showcase workflows that integrate the best parts of Ansible and the HashiCorp stack for configuration and provisioning.
- [Ansible & Terraform – together or against?](https://www.opensourcerers.org/2020/10/12/ansible-and-terraform-integration/): Treat Terraform like any other Ansible module to deploy resources and get the benefit of Terraform like state, dynamic changes to the deployment and even “terraform destroy”. By Götz Rieger.
- [DigitalOcean's How To Use Ansible with Terraform for Configuration Management](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-with-terraform-for-configuration-management): Terraform and Ansible together form a flexible workflow for spinning up servers with the needed software and hardware configurations. Running Ansible directly as part of the Terraform deployment process allows you to have the servers up and bootstrapped with dependencies for your development work and applications much faster.
- [Red Hat and Hashicorp Demo Event](https://primetime.bluejeans.com/a2m/events/playback/e0c34c7f-3cae-4ddc-81ea-ee4d4cc7c91a): By [Michaeld Ford](https://github.com/michaelford85) and Andy James.

## Puppet
- [Migrating from Puppet Enterprise to Ansible Tower](https://www.ansible.com/migrating-from-puppet-enterprise-to-ansible-tower)

## Kubernetes
- [How useful is Ansible in a Cloud-Native Kubernetes Environment?](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

## CMDB
- [Ansible Configuration Management Database](https://github.com/fboender/ansible-cmdb): Ansible-cmdb takes the output of Ansible's fact gathering and converts it into a static HTML overview page (and other things) containing system configuration information.
- [AnsibleDB](https://github.com/apidb-io/ansibledb_opensource): Gives you the ability to quickly collect facts about your Infrastucture estate [linux, windows & network devices] and via our API, pull out the information important to you.

## Performance
- [ansible-trace](https://github.com/mhansen/ansible-trace): Visualise where time is spent in your Ansible playbooks: what tasks, and what hosts, so you can find where to optimise and decrease playbook latency.
- [8 ways to speed up your Ansible playbooks](https://www.redhat.com/sysadmin/faster-ansible-playbook-execution): Integrate appropriate optimization techniques into your Ansible playbooks.
- [5 ways to make your Ansible modules work faster](https://www.redhat.com/sysadmin/faster-ansible-modules): When it comes to complex and lengthy workflows, you need to consider how to optimize the way you use modules so you can speed up your playbooks.

## Windows
- [Windows Ansible Examples](https://github.com/oatakan/windows-ansible-example): Playbook collection by [Orcun Atakan](https://github.com/oatakan).

## Miscellaneous
- [How to make the case for automation architecture: 5 ways to win investment](https://www.redhat.com/architect/automation-architecture): Shifting from personal automation to automation architecture is a systems challenge.
- [An IT executive's guide to automation](https://www.redhat.com/en/resources/executive-guide-to-automation-ebook): Learn the benefits of automation, how IT executives can ensure a successful rollout and adoption, and what to look for in an automation solution.
- [Install Ansible Tower on OpenShift 4.x on your Laptop](https://www.ansiblejunky.com/blog/ansible-tower-in-openshift-on-laptop/)
- [Ansible Semaphore](https://ansible-semaphore.com/): Modern UI for Ansible written in Go.

## My Ansible Content

### Roles
- [grafana_agent](https://galaxy.ansible.com/nleiva/grafana_agent): Installs Grafana Cloud Agent on RedHat/CentOS or Debian/Ubuntu servers to collect observability data and sends it to Grafana Cloud.

### Collections
- [capirca_acl](https://galaxy.ansible.com/nleiva/capirca_acl): This collection includes a module (translate) to use Capirca from your Ansible playbooks.

### Playbooks
- [ansible-kubernetes](https://github.com/nleiva/ansible-kubernetes): Deploy managed Kubernetes clusters in the cloud: AKS, EKS and GKE.
- [ansible-web-server](https://github.com/nleiva/ansible-web-server): Create a highly available web appplication on any cloud provider with Ansible.
- [ansible-webserver-azure](https://github.com/nleiva/ansible-webserver-azure): Automatically provision a number webserver instances behind a load balancer on Azure.
- [ansible-networking](https://github.com/nleiva/ansible-networking): Simple networking examples.
- [ansible-net-modules](https://github.com/nleiva/ansible-net-modules): Network Resource Modules Demo.
- [aws-testbed](https://github.com/nleiva/aws-testbed): Create reproducible Linux environments in the cloud.
- [ansible-cloud](https://github.com/nleiva/ansible-cloud): Deploy virtual machines in AWS (Fedora, JunOS, Cisco IOS, CentOS, etc.).
- [ansible-snow](https://github.com/nleiva/ansible-snow): Ansible Tower workflow with Cisco and Service Now Collections.
- [ansible-backup](https://github.com/nleiva/ansible-backup): Creates a backup of your Tower setup and uploads it to AWS S3.
- [ansible-home](https://github.com/nleiva/ansible-home): Collection of playbooks I run in my personal home-lab.
- [ansible-rhpds](https://github.com/nleiva/ansible-rhpds): Request a Red Hat Product Demo System (RHPDS) Sandbox.
- [ansible-workflow](https://github.com/nleiva/ansible-workflow): An attempt to document Ansible Tower workflows as code.
- [check-calendar](https://github.com/nleiva/check-calendar): Simple app to verify whether a time slot is taken/busy in Google Calendar from Ansible.

### GitHub Actions
- [ansible-lint-action](https://github.com/nleiva/ansible-lint-action): My personal fork to be able to install Ansible collections and any other improvements that might be required.

### Execution Environments
- [Build Execution Environments with GitHub Actions](https://github.com/nleiva/ee-builds)

### Inventories
- [JSON inventory plugin demo](https://github.com/nleiva/inventory): My JSON inventory plugin demo.
- [ansible-inventory](https://github.com/nleiva/ansible-inventory/blob/master/hosts): DevNet always-on Cisco devices.

### Blog Posts
- [A simple approach to delete AWS resources with Ansible](https://nleiva.medium.com/a-simple-approach-to-delete-aws-resources-with-ansible-b31c796fa16d)
- [A beginner's guide to auto-configure a Linux machine with Ansible](https://nleiva.medium.com/a-beginners-guide-to-auto-configure-a-linux-machine-with-ansible-1f4435e8f12e)
- [A simple guide to quickly provisioning AWS resources with Ansible](https://nleiva.medium.com/a-simple-guide-to-quickly-provisioning-aws-resources-with-ansible-35e67ae15b9c)
- [How to consistently run temporary workloads on AWS and save money](https://nleiva.medium.com/how-you-can-consistently-run-temporary-workloads-in-the-cloud-37140b4b5e55)
- [Mapping SAML attributes to Red Hat Ansible Automation Platform organizations and teams](https://www.ansible.com/blog/mapping-saml-attributes-to-red-hat-ansible-automation-platform-organizations-and-teams)
- [5 ways to process JSON data in Ansible](https://opensource.com/article/21/4/process-json-data-ansible)
- [Monitoring your home lab devices in the cloud for free](https://nleiva.medium.com/monitoring-your-home-lab-devices-in-the-cloud-for-free-54c4d11ac471)
- [Create an Ansible module for integrating your Google Calendar](https://opensource.com/article/20/10/ansible-module-go)
- [Integrate your calendar with Ansible to avoid schedule conflicts](https://opensource.com/article/20/10/calendar-ansible)
- [How to make the case for automation architecture: 5 ways to win investment](https://www.redhat.com/architect/automation-architecture)
- [Get Yourself GOing with Ansible](https://codeburst.io/get-yourself-going-with-ansible-60ca623bf4)
- [Ansible and Google Calendar Integration for Change Management](https://medium.com/swlh/ansible-and-google-calendar-integration-for-change-management-7c00553b3d5a)
- [Python and Ansible to automate a Network Security workflow](https://medium.com/swlh/python-and-ansible-to-automate-a-network-security-workflow-28b9a44660c6)
