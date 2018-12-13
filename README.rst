.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

================================
collective.discussion.mentioning
================================

This product introduce mentions in plone.app.discussion 
textarea.

When write comments you can use @ to put a referente to
a site user (eg. @jhonsmith)

The product it's use __ https://www.npmjs.com/package/tributejs
to allow the mention behaviour


Installation
------------

Install collective.discussion.mentioning by adding it to your buildout::

    [buildout]

    ...

    eggs =
        collective.discussion.mentioning


and then running ``bin/buildout``

Finally you can install the product in the portal quickinstaller.
Installing collective.discussion.mentioning will enable comments
globaly

Then in comment you can mention site users


Dependencies
------------

This products has been developed and tested on plone 5.1.4 . 
Other 5.x versions should works.


Contribute
----------

- Issue Tracker: https://github.com/collective/collective.discussion.mentioning/issues
- Source Code: https://github.com/collective/collective.discussion.mentioning


TODO
----

- Add some test


Authors
-------

This product was developed by RedTurtle Technology team.

.. image:: http://www.redturtle.it/redturtle_banner.png
   :alt: RedTurtle Technology Site
   :target: http://www.redturtle.it/


License
-------

The project is licensed under the GPLv2.
