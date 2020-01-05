Xeno Project
==========================

The Xeno Project is based on the ViUR Base repository.
If you want to start a new ViUR project this is the best place to start: `ViUR Base`_


WARNING - WIP
--------------------

Currently this Project is WIP and unstable. Do not use this connector in a production system.

Things that (seams to be) work:
 - user creation / login
 - calling vi with /vi/s/main.html
 - Deferred Tasks

Things that are broken:
 - periodic Tasks
 - Mailing
 - File Handling
 - transactions - maybe.. tests needed
 - relations are totaly untested
 - many more...




Lets Start
--------------------
The easiest way to start the Xeno Project is to check out this repository and use the requirements.txt to install the necessary dependencies.
ATTENTION at this time the original google imports are also imported.

- Then run the clean-base.py and initialize a new project.

- Download a prebuild vi from `ViUR-Website`_.

- Calling the main.py will start the server.

- Currently the port is hardcoded to Port 8080


License
-------

GNU Lesser General Public License v3.0 - See `the LICENSE`_ for more information.

.. _ViUR Base: https://github.com/viur-framework/base
.. _the LICENSE: https://github.com/xeno-project/base/blob/master/LICENSE
.. _ViUR-Website: https://viur.dev/download
