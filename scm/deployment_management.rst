=====================
Deployment Management
=====================

Best Practices
--------------

1. Deployment process is fully automated
2. Rollback process is fully automated
3. Deployment should be unnoticed by users (invisible upgrades)

Deployment Methodologies
------------------------

Invisible Deployment
^^^^^^^^^^^^^^^^^^^^

* Deploying Python without a downtime: deploying-python_

.. _deploying-python: http://philipcristiano.com/2013/06/27/python-gunicorn-deployment.html

Torrent based Deployment
^^^^^^^^^^^^^^^^^^^^^^^^

Torrent methodology is used by Facebook and Twitter and becomes a standard for large scale web sites, below you can read more about this:

Facbook and Torrent deployments:

* facebook-torrent1_
* facebook-torrent2_
* facebook-torrent3_
* facebook-torrent4_
* facebook-torrent5_
* facebook-torrent6_
* facebook-torrent7_

.. _facebook-torrent1: http://arstechnica.com/business/2012/04/exclusive-a-behind-the-scenes-look-at-facebook-release-engineering/3/
.. _facebook-torrent2: http://torrentfreak.com/facebook-uses-bittorrent-and-they-love-it-100625/
.. _facebook-torrent3: http://devopsnet.com/tag/torrent-push/
.. _facebook-torrent4: http://www.andrewhjon.es/deployments-at-facebook
.. _facebook-torrent5: http://agilewarrior.wordpress.com/2011/05/28/how-facebook-pushes-new-code-live/
.. _facebook-torrent6: https://www.facebook.com/video/video.php?v=10100259101684977&oid=9445547199
.. _facebook-torrent7: https://www.facebook.com/note.php?note_id=10150660826788920
