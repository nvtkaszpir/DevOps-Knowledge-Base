==================
Release Management
==================

Articles
--------

* So, What Is It We Do Again?: what-we-do-again_
* Software Release Management Best Practices: release-best-bractices_ 
* Guidelines for building monolithic release management system: release-guidelines_
* Release Trends 2013 by XebiaLabs: release-trends-2013_
* Ubuntu no switching to rolling releases: ubuntu-switch_

.. _what-we-do-again: http://blog.fortified-bikesheds.com/2011/12/so-what-is-it-we-do-again.html
.. _release-best-bractices: http://buildmeister.com/articles/software_release_management_best_practices
.. _release-guidelines: http://www.cmcrossroads.com/article/guidelines-building-monolithic-release-management-system
.. _release-trends-2013: http://go.xebialabs.com/Survey2013.html
.. _ubuntu-switch: http://www.omgubuntu.co.uk/2013/01/ubuntu-not-switching-to-rolling-release-model

Naming Conventions
------------------


Common approach
^^^^^^^^^^^^^^^

* X.0 for Major releases 
* X.X.0 for minor releases 
* X.X.X.0 for patches that don't include functionality updates. 
* X.X.X.X for security and/or emergency patches.

Semantic Versioning
^^^^^^^^^^^^^^^^^^^

Semantic Versioning 2.0.0 (semantic-versioning_)

.. _semantic-versioning: http://semver.org/

Given a version number MAJOR.MINOR.PATCH, increment the:

* MAJOR version when you make incompatible API changes,
* MINOR version when you add functionality in a backwards-compatible manner, and
* PATCH version when you make backwards-compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.
