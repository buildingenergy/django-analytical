django-analytical |latest-version|
==================================

|travis-ci| |coveralls| |health| |python-support| |downloads| |license| |gitter|

The django-analytical application integrates analytics services into a
Django_ project.

.. start docs include

Using an analytics service with a Django project means adding Javascript
tracking code to the project templates.  Of course, every service has
its own specific installation instructions.  Furthermore, you need to
include your unique identifiers, which then end up in the templates.
Not very nice.

This application hides the details of the different analytics services
behind a generic interface, and keeps personal information and
configuration out of the templates.  Its goal is to make the basic
set-up very simple, while allowing advanced users to customize tracking.
Each service is set up as recommended by the services themselves, using
an asynchronous version of the Javascript code if possible.

.. end docs include

.. |latest-version| image:: https://img.shields.io/pypi/v/django-analytical.svg
   :alt: Latest version on PyPI
   :target: https://pypi.python.org/pypi/django-analytical
.. |travis-ci| image:: https://travis-ci.org/jcassee/django-analytical.svg
   :alt: Build status
   :target: https://travis-ci.org/jcassee/django-analytical
.. |coveralls| image:: https://coveralls.io/repos/jcassee/django-analytical/badge.svg
   :alt: Test coverage
   :target: https://coveralls.io/r/jcassee/django-analytical
.. |health| image:: https://landscape.io/github/jcassee/django-analytical/master/landscape.svg?style=flat
   :target: https://landscape.io/github/jcassee/django-analytical/master
   :alt: Code health
.. |python-support| image:: https://img.shields.io/pypi/pyversions/django-analytical.svg
   :target: https://pypi.python.org/pypi/django-analytical
   :alt: Python versions
.. |downloads| image:: https://img.shields.io/pypi/dm/django-analytical.svg
   :alt: Monthly downloads from PyPI
   :target: https://pypi.python.org/pypi/django-analytical
.. |license| image:: https://img.shields.io/pypi/l/django-analytical.svg
   :alt: Software license
   :target: https://github.com/jcassee/django-analytical/blob/master/LICENSE.txt
.. |gitter| image:: https://badges.gitter.im/Join%20Chat.svg
   :alt: Gitter chat room
   :target: https://gitter.im/jcassee/django-analytical
.. _`Django`: http://www.djangoproject.com/

Currently Supported Services
----------------------------

* `Chartbeat`_ traffic analysis
* `Clickmap`_ visual click tracking
* `Clicky`_ traffic analysis
* `Crazy Egg`_ visual click tracking
* `Gaug.es`_ real time web analytics
* `Google Analytics`_ traffic analysis
* `GoSquared`_ traffic monitoring
* `HubSpot`_ inbound marketing
* `Intercom`_ live chat and support
* `KISSinsights`_ feedback surveys
* `KISSmetrics`_ funnel analysis
* `Mixpanel`_ event tracking
* `Olark`_ visitor chat
* `Optimizely`_ A/B testing
* `Performable`_ web analytics and landing pages
* `Piwik`_ open source web analytics
* `Reinvigorate`_ visitor tracking
* `SnapEngage`_ live chat
* `Spring Metrics`_ conversion tracking
* `UserVoice`_ user feedback and helpdesk
* `Woopra`_ web analytics

.. _`Chartbeat`: http://www.chartbeat.com/
.. _`Clickmap`: http://getclickmap.com/
.. _`Clicky`: http://getclicky.com/
.. _`Crazy Egg`: http://www.crazyegg.com/
.. _`Gaug.es`: http://get.gaug.es/
.. _`Google Analytics`: http://www.google.com/analytics/
.. _`GoSquared`: http://www.gosquared.com/
.. _`HubSpot`: http://www.hubspot.com/
.. _`Intercom`: http://www.intercom.io/
.. _`KISSinsights`: http://www.kissinsights.com/
.. _`KISSmetrics`: http://www.kissmetrics.com/
.. _`Mixpanel`: http://www.mixpanel.com/
.. _`Olark`: http://www.olark.com/
.. _`Optimizely`: http://www.optimizely.com/
.. _`Performable`: http://www.performable.com/
.. _`Piwik`: http://www.piwik.org/
.. _`SnapEngage`: http://www.snapengage.com/
.. _`Spring Metrics`: http://www.springmetrics.com/
.. _`UserVoice`: http://www.uservoice.com/
.. _`Woopra`: http://www.woopra.com/

Documentation and Support
-------------------------

The documentation can be found in the ``docs`` directory or `read
online`_.  The source code and issue tracker are generously `hosted by
GitHub`_.  Bugs should be reported there, whereas for lengthy chats
and coding support when implementing new service integrations you're
welcome to use our `Gitter chat room`_.

.. _`read online`: https://packages.python.org/django-analytical/
.. _`hosted by GitHub`: https://github.com/jcassee/django-analytical
.. _`Gitter chat room`: https://gitter.im/jcassee/django-analytical

How To Contribute
-----------------

.. start contribute include

If you want to help out with the development of django-analytical, by
posting detailed bug reports, proposing new features or other analytics
services to support, or suggesting documentation improvements, use the
`issue tracker`_.  If you want to get your hands dirty, great!  Clone
the repository, make changes and place a `pull request`_.  Creating an
issue to discuss your plans is useful.

.. _`issue tracker`: https://github.com/jcassee/django-analytical/issues
.. _`pull request`: https://github.com/jcassee/django-analytical/pulls

.. end contribute include
