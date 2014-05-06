==================
Release Management
==================

Best Practices
--------------


* Release Management Best Practices: release-best-practices_

.. _release-best-practices: http://www.cmnogueira.pt/2014/04/03/release-deployment-management-best-practices/


Articles
--------

* Stop Blaming Release Management: stop-blaming-rm_
* So, What Is It We Do Again?: what-we-do-again_
* Software Release Management Best Practices: release-best-bractices_ 
* Guidelines for building monolithic release management system: release-guidelines_
* Release Trends 2013 by XebiaLabs: release-trends-2013_
* Ubuntu no switching to rolling releases: ubuntu-switch_

.. _stop-blaming-rm: http://www.theitsmreview.com/2014/03/stop-blaming-release-management/
.. _what-we-do-again: http://blog.fortified-bikesheds.com/2011/12/so-what-is-it-we-do-again.html
.. _release-best-bractices: http://buildmeister.com/articles/software_release_management_best_practices
.. _release-guidelines: http://www.cmcrossroads.com/article/guidelines-building-monolithic-release-management-system
.. _release-trends-2013: http://go.xebialabs.com/Survey2013.html
.. _ubuntu-switch: http://www.omgubuntu.co.uk/2013/01/ubuntu-not-switching-to-rolling-release-model

Naming Conventions
------------------


Versioning
^^^^^^^^^^

Most common model:

* X.0 for Major releases 
* X.X.0 for minor releases 
* X.X.X.0 for patches that don't include functionality updates. 
* X.X.X.X for security and/or emergency patches.

Other models:

* Git 1.9 Versioning: git-1.9-versioning_
* Gnome Versioning: gnome-versioning_
* Maven Versioning: maven-versioning_
* Semantic Versioning 2.0.0: semantic-versioning_


.. _git-1.9-versioning: http://article.gmane.org/gmane.linux.kernel/1638649
.. _gnome-versioning: http://www106.pair.com/rhp/parallel.html
.. _maven-versioning: http://docs.codehaus.org/display/MAVEN/Versioning
.. _semantic-versioning: http://semver.org/


Given a version number MAJOR.MINOR.PATCH, increment the:

* MAJOR version when you make incompatible API changes,
* MINOR version when you add functionality in a backwards-compatible manner, and
* PATCH version when you make backwards-compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.


Tools
-----

Gitver
^^^^^^

A very simple, lightweight, tag-based version string manager for git, written in Python.

Homepage: https://github.com/manuelbua/gitver
