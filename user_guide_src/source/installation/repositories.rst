CodeIgniter Repositories
########################

The CodeIgniter 4 open source project has its own
`GitHub organization <https://github.com/codeigniter4>`_.

There are several development repositories, of interest to potential contributors:

+---------------------------------------------------------------------+--------------+-----------------------------------------------------------------+
| Repository                                                          | Audience     | Description                                                     |
+=====================================================================+==============+=================================================================+
| CodeIgniter4                                                        | contributors | Project codebase, including tests & user guide sources          |
+---------------------------------------------------------------------+--------------+-----------------------------------------------------------------+
| translations                                                        | developers   | System message translations                                     |
+---------------------------------------------------------------------+--------------+-----------------------------------------------------------------+
| `coding-standard <https://github.com/CodeIgniter/coding-standard>`_ | contributors | Coding style conventions & rules                                |
+---------------------------------------------------------------------+--------------+-----------------------------------------------------------------+

There are also several deployment repositories, referenced in the installation directions.
The deployment repositories are built automatically when a new version is released, and they
are not directly contributed to.

+------------------+--------------+-----------------------------------------------------------------+
| Repository       | Audience     | Description                                                     |
+==================+==============+=================================================================+
| framework        | developers   | Released versions of the framework                              |
+------------------+--------------+-----------------------------------------------------------------+
| appstarter       | developers   | Starter project (app/public/writable).                          |
|                  |              | Dependent on "framework"                                        |
+------------------+--------------+-----------------------------------------------------------------+
| userguide        | anyone       | Pre-built user guide                                            |
+------------------+--------------+-----------------------------------------------------------------+

In all the above, the latest version of a repository can be downloaded
by selecting the "releases" link in the secondary navbar inside
the "Code" tab of its GitHub repository page. The current (in development) version of each can
be cloned or downloaded by selecting the "Clone or download" dropdown
button on the right-hand side if the repository homepage.

Composer Packages
=================

We also maintain composer-installable packages on `packagist.org <https://packagist.org/search/?query=codeigniter4>`_.
These correspond to the repositories mentioned above:

- `codeigniter4/framework <https://packagist.org/packages/codeigniter4/framework>`_
- `codeigniter4/appstarter <https://packagist.org/packages/codeigniter4/appstarter>`_
- `codeigniter4/translations <https://packagist.org/packages/codeigniter4/translations>`_
- `codeigniter/coding-standard  <https://packagist.org/packages/codeigniter/coding-standard>`_

See the :doc:`Installation </installation/index>` page for more information.

CodeIgniter 4 Projects
======================

We maintain a `codeigniter4projects <https://github.com/codeigniter4projects>`_ organization
on GitHub as well, with projects that are not part of the framework,
but which showcase it or make it easier to work with!

+------------------+--------------+-----------------------------------------------------------------+
| Repository       | Audience     | Description                                                     |
+==================+==============+=================================================================+
| website2         | developers   | The codeigniter.com website, written in CodeIgniter 4           |
+------------------+--------------+-----------------------------------------------------------------+
| playground       | developers   | Basic code examples in project form. Still growing.             |
+------------------+--------------+-----------------------------------------------------------------+

These are not composer-installable repositories.
