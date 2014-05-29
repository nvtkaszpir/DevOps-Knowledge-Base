============================
Infrastructure Orchestration
============================

The concept of Infrastructure Orchestration was previously known as Environment Configuration. Many people and organizations are still using the old name, but for purpose of this SCM Knowledge Base We will stick with the newest trend as it is getting more and more popular with every month.

Best Practices
--------------

1. Configuration treated as a Source Code
2. Communication of configuration changes

Articles
--------

* Chicken or Egg: Abstraction and Automation: chicken-or-egg-abstraction-and_
* Manage Resources like a Hotel: infrastructure-like-a-hotel_

.. _chicken-or-egg-abstraction-and: http://java.dzone.com/articles/chicken-or-egg-abstraction-and
.. _infrastructure-like-a-hotel: http://www.cloudsidekick.com/blog/manage-resources-like-a-hotel.html


Frameworks
----------

Comparisons
^^^^^^^^^^^

* Comparison Grid for Ansible / SaltStack / Chef / Puppet: comparison-grid_
* Comparison of open-source configuration management software: wikipedia_
* Ansible and Salt: A detailed comparison: ansible-and-salt_

.. _comparison-grid: https://devopsu.com/books/Taste-Test-Quick-Look-Grid.pdf
.. _wikipedia: http://en.wikipedia.org/wiki/Comparison_of_open-source_configuration_management_software
.. _ansible-and-salt: https://missingm.co/2013/06/ansible-and-salt-a-detailed-comparison/

Salt Stack
^^^^^^^^^^

Salt is an open source tool to manage your infrastructure. Easy enough to get running in minutes and fast enough to manage tens of thousands of servers (and still get a response back in seconds). Execute arbitrary shell commands or choose from dozens of pre-built modules of common (or complex) commands. Target individual servers or groups of servers based on name, defined roles, or a variety of system information such as hardware, software, operating system, current version, current environment, and many more.

* SaltStack setup on beaglebone black rev c debian arm: salt-arm_
* Home Page: salt-homepage_
* Salt to the Rescue: salt-to-the-rescue_

.. _salt-arm: http://vmsec.wordpress.com/2014/05/25/salt-stack-setup-on-beaglebone-black-rev-c-debian-arm/
.. _salt-homepage: http://saltstack.org/
.. _salt-to-the-rescue: http://www.lecloud.net/post/29325359938/salt-to-the-rescue

Salt Tutorials
^^^^^^^^^^^^^^

* Deploy & Orchestrate infrastructures on Cloud Providers: orchestrate-cloud_
* Salt and OpenERP Tutorial: salt-openerp_
* Salt targeting: salt-targeting_
* Salt states: salt-states_
* Getting started with Salt: getting-started-salt_
* Deploying Django with Saltstack: django-with-salt_
* Tutorial: salt-tutorial_

.. _orchestrate-cloud: http://walterdalmut.com/2014/05/26/cloudparty-2014-deploy-orchestrate-infrastructures-on-cloud-providers/#more-1718
.. _salt-openerp: http://blog.warehouseman.com/2014/02/step-00-handbook-for-devops-for-openerp.html
.. _salt-targeting: http://www.wekanban.com/saltstack-targeting-minion-part-1/
.. _salt-states: http://www.wekanban.com/salt-states/
.. _getting-started-salt: http://www.linuxjournal.com/content/getting-started-salt-stack-other-configuration-management-system-built-python
.. _django-with-salt: http://www.barrymorrison.com/2013/Mar/11/deploying-django-with-salt-stack/
.. _salt-tutorial: http://27escape.blogspot.be/2013/08/basic-salt-tutorial.html

Usage Examples
""""""""""""""

* Salt and XMPP integartion: salt-and-xmpp_
* Salt and Continuous Deployment: salt-continuous-deployment_

.. _salt-and-xmpp: http://hveem.no/salt-xmpp-gateway
.. _salt-continuous-deployment: https://rudd-o.com/linux-and-free-software/heard-of-the-salt-stack-or-the-go-programming-language

Propaganda
""""""""""

* Hello SaltStack: hello-salt-stack_
* Salty infrastructure: salty-infrastructure_

.. _hello-salt-stack: http://www.willdurness.com/tech/so-long-puppet-hello-salt-stack/
.. _salty-infrastructure: http://mark-rogers.net/blog/2013/04/07/salty-infrastructure/


Vagrant
^^^^^^^

Vagrant is a development tool which stands on the shoulders of giants, using tried and proven technologies to achieve its magic. Vagrant uses Oracle’s VirtualBox to create its virtual machines and then uses Chef or Puppet to provision them. By providing easy to configure, lightweight, reproducible, and portable virtual machines targeted at development environments, Vagrant helps maximize the productivity and flexibility of you and your team.

Vagrant Homepage: vagrant-homepage_

.. _vagrant-homepage: http://www.vagrantup.com/

* Why Vagrant is the Best DevOps Tool Ever: vagrant-devops-tool_
* Vagrant 1.5 and Vagrant Cloud: vagrant-1.5_
* Vagrant with OpenDaylight: vagrant-with-opendaylight_

.. _vagrant-devops-tool: http://blog.ingineering.it/post/81406512594/why-vagrant-is-the-best-devops-tool-ever
.. _vagrant-1.5: http://www.vagrantup.com/blog/vagrant-1-5-and-vagrant-cloud.html
.. _vagrant-with-opendaylight: http://fredhsu.wordpress.com/2013/11/04/vagrant-with-opendaylight/


Puppet
^^^^^^

Puppet is IT automation software that helps system administrators manage infrastructure throughout its lifecycle, from provisioning and configuration to patch management and compliance. Using Puppet, you can easily automate repetitive tasks, quickly deploy critical applications, and proactively manage change, scaling from 10s of servers to 1000s, on-premise or in the cloud.

* Puppet Homepage: puppet-homepage_
* Testing Puppet's custom facts with RSpec: puppet-rspec_

.. _puppet-homepage: http://puppetlabs.com/
.. _puppet-rspec: http://unethicalblogger.com/2014/03/01/testing-custom-facts-with-rspec.html


Capistrano
^^^^^^^^^^

Capistrano is a utility and framework for executing commands in parallel on multiple remote machines, via SSH. It uses a simple DSL (borrowed in part from Rake) that allows you to define tasks, which may be applied to machines in certain roles. It also supports tunneling connections via some gateway machine to allow operations to be performed behind VPN's and firewalls. Capistrano was originally designed to simplify and automate deployment of web applications to distributed environments, and originally came bundled with a set of tasks designed for deploying Rails applications.

* Capistrano Homepage: capistrano-homepage_
* Webistrano Homepage (Capistrano's web GUI): webistrano-homepage_

.. _capistrano-homepage: https://github.com/capistrano/capistrano
.. _webistrano-homepage:  https://github.com/peritor/webistrano#readme

Fabric
^^^^^^

Fabric is a Python (2.5 or higher) library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks. It provides a basic suite of operations for executing local or remote shell commands (normally or via sudo) and uploading/downloading files, as well as auxiliary functionality such as prompting the running user for input, or aborting execution.

Fabric Homepage: fabric-homepage_

.. _fabric-homepage: http://docs.fabfile.org/en/1.5/

Ubuntu's juju
^^^^^^^^^^^^^

* juju used for Jenkins deployment: juju-jenkins_

.. _juju-jenkins: https://wiki.jenkins-ci.org/display/JENKINS/Installing+Jenkins+on+Ubuntu

Glu
^^^

Glu takes a very declarative approach, in which you describe/model what you want, and glu can then:

* compute the set of actions to deploy/upgrade your applications
* ensure that it remains consistent over time
* detect and alert you when there is a mismatch

Glu Homepage: glu-homepage_

.. _glu-homepage: http://linkedin.github.com/glu/docs/latest/html/index.html

Ansible
^^^^^^^

It turns out, that about the same time I did look around, a new alternative was launched called Ansible, written in Python. I haven’t done a lot with it yet. But I really like what I’ve seen so far, and the design principles really resonates with me. The easiest config management system to use, ever. Requires no software to be installed on the remote box for bootstrapping Idempotent modules (although you can choose whether or not to have this for your own modules) I think the author Michael DeHaan sums it up really good in this interview:

* A look at Ansible: look-at-ansible_

.. _look-at-ansible: http://www.lexicallyscoped.com/2013/03/17/ansible.html

Chef
^^^^

* Using Test Doubles in ChefSpec: stubs-and-doubles_

.. _stubs-and-doubles: http://www.agilesysadmin.net/stubs-and-doubles-in-chefspec

Nix
^^^

Nix Homepage: nix-homepage_

* Why Puppet/Chef/Ansible aren't good enough: nix-vs-other_

.. _nix-homepage: http://nixos.org/nix/
.. _nix-vs-other: https://www.domenkozar.com/2014/03/11/why-puppet-chef-ansible-arent-good-enough-and-we-can-do-better/

Gunnery
^^^^^^^

Gunnery is multipurpose task execution tool for distributed systems: gunnery-homepage_

.. _gunnery-homepage: http://eyjafjallajokull.github.io/gunnery


Rundeck
^^^^^^^

Rundeck Homepage: rundeck-homepage_

.. _rundeck-homepage: http://rundeck.org/

Network
-------

* Cisco - Image Hosting Service Implements Flexible Cloud Infrastructure: cisco-salt_
* Automation for Network Engineers: automation-for-network_

.. _cisco-salt: http://www.cisco.com/c/dam/en/us/solutions/collateral/switches/catalyst-6500-series-switches/photobucket_external_casestudy.pdf
.. _automation-for-network: http://packetpushers.net/show-176-intro-to-python-automation-for-network-engineers/

Scaling
-------

* Autoscaling Best Practices: autoscaling-best-practices_

.. _autoscaling-best-practices: http://www.slideshare.net/lynxmanuk/autoscaling-best-practices
