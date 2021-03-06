#######################
LSST DM Developer Guide
#######################

This is an internal guide for `LSST DM <https://www.lsst.org/about/dm>`_ staff.
It's also openly available so that others can understand how we're building the LSST's data management subsystem.

This guide includes a mix of normative requirements and helpful, descriptive, pages.
When it's particularly important that you closely follow a standard, we include an annotation box at the top of the page.

Any member of DM can contribute to this guide.
It's published from the https://github.com/lsst-dm/dm_dev_guide GitHub repo.
Check out the `README <https://github.com/lsst-dm/dm_dev_guide/blob/master/README.md>`__ to get started.

****

**Jump to:** :ref:`Team <part-team>` · :ref:`Communications <part-communications>` · :ref:`Project documentation <part-project-docs>` · :ref:`Work management <part-work>`

**Development guides:** :ref:`Overview <part-guides>` · :ref:`C++ <part-cpp>` · :ref:`Python <part-python>` · :ref:`Pybind11 <part-pybind11>` · :ref:`JavaScript <part-javascript>` · :ref:`ReStructuredText <part-rst>` · :ref:`DM Stack <part-dm-stack>` · :ref:`Git <part-git>` · :ref:`Editors <part-editors>`

**Services:** :ref:`Overview <part-services>` · :ref:`Jenkins <part-jenkins>` · :ref:`LSST Data Facility <part-ldf>`

****

.. TEAM SECTION ==============================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Team
   :hidden:

   team/onboarding
   team/code-of-conduct
   team/empowerment
   team/drp

.. Table of contents published on the homepage.
.. Mirror changes here to team/index.rst (temporary workflow)

.. _part-team:

Team
====

Basic information about the LSST Data Management Subsystem and our culture.
Learn more about the Data Management Subsystem in :ldm:`294`.

- :doc:`team/onboarding`
- :doc:`team/code-of-conduct`
- :doc:`team/empowerment`

Team-specific pages:

- :doc:`team/drp`

.. COMMUNICATIONS SECTION ====================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Communications
   :hidden:

   communications/slack-github-username.rst
   communications/rfc.rst
   communications/rfd.rst
   communications/wiki.rst
   communications/presenting-at-conferences.rst

.. Table of contents published on the homepage.
.. Mirror changes here to team/index.rst (temporary workflow)

.. _part-communications:

Communications
==============

How to use DM's communication channels.

- :doc:`communications/slack-github-username`
- :doc:`communications/rfc`
- :doc:`communications/rfd`
- :doc:`communications/wiki`
- :doc:`communications/presenting-at-conferences`

.. PROJECT DOCS SECTION ======================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Project docs
   :hidden:

   project-docs/change-controlled-docs.rst
   project-docs/publication-policy.rst
   project-docs/technotes.rst

.. _part-project-docs:

Project documentation
=====================

Controlled documentation and publications.

- :doc:`project-docs/change-controlled-docs`
- :doc:`project-docs/publication-policy`

Technical notes.

- :doc:`project-docs/technotes`

.. WORK MANAGEMENT SECTION ===================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Work
   :hidden:

   work/flow.rst
   work/project-planning.rst
   work/jira-agile.rst
   work/jira-tips.rst

.. _part-work:

Work management
===============

How DM coordinates work and gets things done.

- :doc:`work/flow`
- :doc:`work/project-planning`
- :doc:`work/jira-agile`
- :doc:`work/jira-tips`

.. -------------------

.. _part-guides:

Development guides
==================

.. DEVELOPMENT OVERVIEW SECTION ==============================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Code Style Guides
   :hidden:

   coding/intro.rst
   coding/unit-test-policy.rst

.. _part-dev-guides-overview:

Overview of Code Style Guides & Policies
----------------------------------------

- :doc:`coding/intro`
- :doc:`coding/unit-test-policy`

.. C++ SECTION ===============================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: C++
   :hidden:

   cpp/style
   cpp/api-docs
   cpp/clang-format
   cpp/testing-private-functions
   cpp/templates
   cpp/boost
   cpp/eigen
   cpp/profiling

.. _part-cpp:

C++
---

- :doc:`cpp/style`
- :doc:`cpp/api-docs`
- :doc:`cpp/clang-format`
- :doc:`cpp/testing-private-functions`
- :doc:`cpp/templates`
- :doc:`cpp/boost`
- :doc:`cpp/eigen`
- :doc:`cpp/profiling`

.. PYTHON SECTION ============================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Python
   :hidden:

   python/style
   python/testing
   python/numpydoc
   python/astropy
   python/profiling

.. _part-python:

Python
------

- :doc:`python/style`
- :doc:`python/testing`
- :doc:`python/numpydoc`
- :doc:`python/astropy`
- :doc:`python/profiling`

.. PYBIND11 SECTION ==========================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Pybind11
   :hidden:

   pybind11/style
   pybind11/how-to

.. _part-pybind11:

Pybind11
--------

- :doc:`pybind11/style`
- :doc:`pybind11/how-to`

.. JAVASCRIPT SECTION ========================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: JavaScript
   :hidden:

   javascript/jsdoc

.. _part-javascript:

JavaScript
----------

- :doc:`javascript/jsdoc`

.. RESTRUCTUREDTEXT SECTION ==================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: ReStructuredText
   :hidden:

   restructuredtext/style

.. _part-rst:

ReStructuredText
----------------

- :doc:`restructuredtext/style`

.. STACK SECTION =============================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: DM Stack
   :hidden:

   stack/platforms
   stack/transferring-code
   stack/package-docs
   stack/logging
   stack/debug
   stack/jenkins-stack-os-matrix
   stack/unit-test-coverage.rst
   stack/eups-tutorial
   stack/lsstsw
   stack/adding-a-new-package
   stack/packaging-third-party-eups-dependencies
   stack/renaming-a-package

.. _part-dm-stack:

DM Stack
--------

General policies and procedures.

- :doc:`stack/platforms`
- :doc:`stack/transferring-code`

Development.

- :doc:`stack/package-docs`
- :doc:`stack/logging`
- :doc:`stack/debug`

Testing.

- :doc:`stack/jenkins-stack-os-matrix`
- :doc:`stack/unit-test-coverage`

Packaging.

- :doc:`stack/eups-tutorial`
- :doc:`stack/lsstsw`
- :doc:`stack/adding-a-new-package`
- :doc:`stack/packaging-third-party-eups-dependencies`
- :doc:`stack/renaming-a-package`

.. GIT SECTION ===============================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Git
   :hidden:

   git/setup
   git/git-lfs

.. _part-git:

Git
---

- :doc:`git/setup`
- :doc:`git/git-lfs`

.. EDITORS SECTION ===========================================================

.. Hidden toctree to manage the sidebar navigation. Match the contents list below.

.. toctree::
   :maxdepth: 1
   :caption: Editors
   :hidden:

   editors/emacs
   editors/sublime
   editors/vim

.. _part-editors:

Editors
-------

Crowd-sourced recommendations for configuring editors for LSST development (listed alphabetically)

- :doc:`editors/emacs`
- :doc:`editors/sublime`
- :doc:`editors/vim`

.. _part-services:

Service guides
==============

.. OVERVIEW SECTION ==========================================================

.. toctree::
   :maxdepth: 1
   :caption: IT Overview
   :hidden:

   it/itsc

.. _part-it:

IT overview
-----------

- :doc:`it/itsc`

.. JENKINS SECTION ===========================================================

.. toctree::
   :maxdepth: 1
   :caption: Jenkins
   :hidden:

   jenkins/getting-started

.. _part-jenkins:

Jenkins CI
----------

- :doc:`jenkins/getting-started`

.. NCSA/LDF SERVICES SECTION =================================================

.. toctree::
   :maxdepth: 1
   :caption: LDF Services
   :hidden:

   services/lsst-dev
   services/lsst-db
   services/verification
   services/datasets
   services/data_protection
   services/ncsa_bulk_transfer
   services/nebula/index
   services/orchestration/index

.. _part-ldf:

LSST Data Facility services
---------------------------

- :doc:`services/lsst-dev`
- :doc:`services/lsst-db`
- :doc:`services/verification`
- :doc:`services/datasets`
- :doc:`services/data_protection`
- :doc:`services/ncsa_bulk_transfer`
- :doc:`services/nebula/index`
- :doc:`services/orchestration/index`
