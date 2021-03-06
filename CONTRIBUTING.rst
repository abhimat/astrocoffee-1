============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given. 

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/ajshajib/astrocoffee/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "feature"
is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

AstroCoffee could always use more documentation, whether as part of the 
official AstroCoffee docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/ajshajib/astrocoffee/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `astrocoffee` for
local development.

1. Fork_ the `astrocoffee` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/astrocoffee.git

3. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

 The branch names should be in 'bugfix/fix-a-bug' or 'feature/add-a-feature' format. Now you can make your changes locally.

4. When you're done making changes, check that your changes pass style and unit
   tests, including testing other Python versions with tox::

    $ tox

To get tox, just pip install it.

5. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

6. Submit a pull request through the GitHub website.

.. _Fork: https://github.com/Nekroze/astrocoffee/fork

Styling Guidelines
------------------

AstroCoffee is written in Python and we want to keep it Pythonic. Generally, we try
to follow PEP 8_, 257_, and 287_ as closely as possible. A few key points,
that need to be emphasized or are beyond these PEPs, are

1. Use full words for variable and function/method names with words separated by underscore. Function/method names must start with a verb.
2. Class variables and functions/methods that are not intended for use outside of the class/module must be named with a starting underscore.
3. No Python lines must be more than 79 characters in length.
4. Commit messages should be in this format::

    Write commit subject line

    This is an example commit message. Start the commit subject line with
    a verb. All the verbs are in command form, e.g. fix, add; not in other
    forms, e.g. fixes, added. The subject line has no period at the end and
    is followed by a blank line. Add a detailed description about what the
    commit does in a paragraph after that. No lines in the whole commit
    message must be more than 72 characters in length.

5. When in doubt, follow the styling guidelines of the existing code.

.. _8: https://www.python.org/dev/peps/pep-0008/
.. _257: https://www.python.org/dev/peps/pep-0257/
.. _287: https://www.python.org/dev/peps/pep-0287/

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 2.6, 2.7, and 3.6, and for PyPy.
   Check https://travis-ci.org/ajshajib/astrocoffee 
   under pull requests for active pull requests or run the ``tox`` command and
   make sure that the tests pass for all supported Python versions.

Tips
----

To run a subset of tests::

	 $ py.test test/test_astrocoffee.py
