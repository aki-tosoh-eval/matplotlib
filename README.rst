|PyPi|_ |Downloads|_ |NUMFocus|_

|DiscourseBadge|_ |Gitter|_ |GitHubIssues|_ |GitTutorial|_

|Travis|_ |AzurePipelines|_ |AppVeyor|_ |Codecov|_ |LGTM|_

.. |Travis| image:: https://travis-ci.com/matplotlib/matplotlib.svg?branch=master
.. _Travis: https://travis-ci.com/matplotlib/matplotlib

.. |AzurePipelines| image:: https://dev.azure.com/matplotlib/matplotlib/_apis/build/status/matplotlib.matplotlib?branchName=master
.. _AzurePipelines: https://dev.azure.com/matplotlib/matplotlib/_build/latest?definitionId=1&branchName=master

.. |AppVeyor| image:: https://ci.appveyor.com/api/projects/status/github/matplotlib/matplotlib?branch=master&svg=true
.. _AppVeyor: https://ci.appveyor.com/project/matplotlib/matplotlib

.. |Codecov| image:: https://codecov.io/github/matplotlib/matplotlib/badge.svg?branch=master&service=github
.. _Codecov: https://codecov.io/github/matplotlib/matplotlib?branch=master

.. |LGTM| image:: https://img.shields.io/lgtm/grade/python/g/matplotlib/matplotlib.svg?logo=lgtm&logoWidth=18
.. _LGTM: https://lgtm.com/projects/g/matplotlib/matplotlib

.. |DiscourseBadge| image:: https://img.shields.io/badge/help_forum-discourse-blue.svg
.. _DiscourseBadge: https://discourse.matplotlib.org

.. |Gitter| image:: https://badges.gitter.im/matplotlib/matplotlib.svg
.. _Gitter: https://gitter.im/matplotlib/matplotlib

.. |GitHubIssues| image:: https://img.shields.io/badge/issue_tracking-github-blue.svg
.. _GitHubIssues: https://github.com/matplotlib/matplotlib/issues

.. |GitTutorial| image:: https://img.shields.io/badge/PR-Welcome-%23FF8300.svg?
.. _GitTutorial: https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project

.. |PyPi| image:: https://badge.fury.io/py/matplotlib.svg
.. _PyPi: https://badge.fury.io/py/matplotlib

.. |Downloads| image:: https://pepy.tech/badge/matplotlib/month
.. _Downloads: https://pepy.tech/project/matplotlib/month

.. |NUMFocus| image:: https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A
.. _NUMFocus: http://www.numfocus.org


##########
Matplotlib
##########

Matplotlib is a Python 2D plotting library which produces publication-quality
figures in a variety of hardcopy formats and interactive environments across
platforms. Matplotlib can be used in Python scripts, the Python and IPython
shell (à la MATLAB or Mathematica), web application servers, and various
graphical user interface toolkits.

NOTE: The current master branch is now Python 3 only.  Python 2 support is
being dropped.

`Home page <http://matplotlib.org/>`_

Install
=======

For installation instructions and requirements, see the INSTALL.rst file or the
`install <http://matplotlib.org/users/installing.html>`_ documentation. If you
think you may want to contribute to matplotlib, check out the `guide to
working with the source code
<http://matplotlib.org/devel/gitwash/index.html>`_.

Test
====

After installation, you can launch the test suite::

  pytest

Or from the Python interpreter::

  import matplotlib
  matplotlib.test()

Consider reading http://matplotlib.org/devel/coding_guide.html#testing for more
information. Note that the test suite requires pytest. Please install with pip
or your package manager of choice.

Contact
=======
`Discourse <https://discourse.matplotlib.org/>`_ is the discussion forum for general questions and discussions and our recommended starting point.

Our active mailing lists (which are mirrored on Discourse) are:

* `Users <https://mail.python.org/mailman/listinfo/matplotlib-users>`_ mailing list: matplotlib-users@python.org
* `Announcement  <https://mail.python.org/mailman/listinfo/matplotlib-announce>`_ mailing list: matplotlib-announce@python.org
* `Development <https://mail.python.org/mailman/listinfo/matplotlib-devel>`_ mailing list: matplotlib-devel@python.org


Gitter_ is for coordinating development and asking questions directly related
to contributing to matplotlib.

Contribute
==========
You've discovered a bug or something else you want to change - excellent!

You've worked out a way to fix it – even better!

You want to tell us about it – best of all!

Start at the `contributing guide <http://matplotlib.org/devdocs/devel/contributing.html>`_!

Developer notes are now at `Developer Discussions <https://github.com/orgs/matplotlib/teams/developers/discussions>`_ (Note: For technical reasons, this is currently only accessible for matplotlib developers.)

Citing Matplotlib
=================
If Matplotlib contributes to a project that leads to publication, please
acknowledge this by citing Matplotlib.
`A ready-made citation entry <https://matplotlib.org/citing.html>`_ is available. :)
