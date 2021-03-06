################
JIRA Agile Usage
################

Refer to `DMTN-020 <https://dmtn-020.lsst.io/>`_ for detailed information on
the JIRA-based planning process used by DM.

Key Concepts
============

- Cycles (aka Releases) occur every 6 months.
- Sprints are monthly, fixed timeframes.
- Epics are higher-level features or capabilities that are to be delivered in a
  cycle.  Epic names should be of the form "Area Short Description" (e.g.
  Database qserv refactor)
- Stories describe concrete, demonstrable features to be delivered in a single
  sprint.
- Story points are to be assigned at 2 story points per full-time day of an
  appropriate developer.
- Stories and story points should not be changed once work on a story has
  started.

.. _jira-teams:

Teams
=====

The JIRA “team” field is used to define financial and managerial responsibility for getting the work done.
We recognise the following teams:

================================== ===================
Team Name                          Responsible Manager
================================== ===================
System Management                  Wil O'Mullane
DM Science                         Mario Juric
Architecture                       K-T Lim
Alert Production                   John Swinbank
Data Release Production            John Swinbank
Science User Interface             Xiuqin Wu
Data Access and Database           Fritz Mueller
Data Facility                      Margaret Gelman
International Comms and Base Site  Jeff Kantor
SQuaRE                             Frossie Economou
External                           None (see below)
================================== ===================

The “External” team is used to label work done by individuals who are not funded by LSST.

.. _jira-labels:

Labels
======

We support and encourage the use of labels to group related tickets.
Their use is not formally restricted or regulated.
However, there are a few labels which are of general interest:

=================== =============================================================================
Label               Meaning
=================== =============================================================================
``dm-sst``          This work is of interest to the DM System Science Team.
``dm-set``          This work is of interest to the DM Systems Engineering Team.
``dmlt``            This work is of interest to the DM Leadership Team.
``gen3-middleware`` Work on the “generation 3” Butler and associated middleware (e.g. SuperTask).
=================== =============================================================================
