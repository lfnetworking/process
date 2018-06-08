*********************
Project Data Template
*********************

Instructions
------------

This document is a template to collect the data LFN thinks are relevant to LFN
Project health. Projects will copy this template and instantiate it with their
data as a part applying for lifecycle state transitions.

  mkdir -p <relevant lifecycle transition dir>/<project name>/
  cp project_data_template.rst !$/project_data.rst

If the project has instantiated this template before they are welcome to start
from that base and update it with any new information. Be sure that the data
requested by the primary copy of the Project Data Template has not changed.

These instructions should be removed from the instantiated template.

Project Data
------------

Data that describes a Linux Foundation Networking Project. Provide links to
authoritative public content or steps to reproduce results when possible.

Project Vitals
==============

Basic information about the candidate project.

* Project name
* Project creation date
* Project license
* Project release schedule

  * History of at least two years or age of project
  * Planned future release schedule

* Statement of alignment with LFN Charter/Mission

Community Historical Trends
===========================

History of the candidate project's community.

For each release or year for at least the last two years or the lifespan of the
project, provide the following.

* Contribution statistics

  * Number of commits
  * Number of non-trivial (generated code, version bump, ...) commits >5k LoC

    * Merged by uploader
    * Merged by committer from same organization as uploader
    * Merged without substantial code review
    * If the candidate project has sub-projects, group these by sub-project

  * Number of commits per-organization

* Contributor statistics

  * Number of contributors
  * Number of contributors per-organization

Community Current Status
========================

Snapshot of the candidate project's community.

* Committer statistics

  * Number of committers
  * Number of committers per-organization
  * Number of active committers
  * Number of active committers per-organization

* Contributor approval process

  * Contributor eligibility
  * Process to become a contributor
  * Process to remove a contributor

* Committer approval process

  * Committer eligibility
  * Process to become a committer
  * Process to remove a committer

* Project governance structure

  * Summery of project governance structure
  * Summery of how project governance was established and can be modified
  * Links to all public project governance documentation
  * List of all community roles and details of how they are filled/emptied
  * List of community roles that are elected
  * List of community roles that are appointed
  * List of people in all community roles and their organization affiliation

* User community

  * Summary of project user community

Project Functionality
=====================

Details about the functionality of the candidate project.

* Summary of candidate project functionality
* Summary of candidate project technology components and purposes
* Summary of where candidate project complements functionality already provided
  by project(s) within LFN
* Summary of where candidate project overlaps functionality already provided by
  project(s) within LFN

Project Tooling
===============

Details about the tooling used by the candidate project.

* Bug tracker

  * Links to bug trackers used by the candidate project.
  * Integrated with any other relevant projects?
  * To what extent are external/private bug trackers used?

* Chat tooling

  * Links to chat tooling used by the project.
  * Overview of chat tooling used by the candidate project.
  * To what extent is external/private chat tooling used?

* Code repositories

  * Links to code repositories used by the candidate project.
  * Overview of code repositories used by the candidate project.
  * To what extent are external/private code repositories used?

* Code review

  * Links to code review systems used by the candidate project.
  * Overview of code review norms, practices, conventions, rules.
  * To what extent are external/private code review systems used?

* Continuous Integration tooling

  * Links to CI jobs.
  * Links to CI job definitions, infrastructure configuration.
  * Overview of CI related to the candidate project.
  * To what extent are external/private CI systems used?

* Documentation

  * Links to documentation for the candidate project.

* Mailing lists

  * Links to mailing lists used by the project and their archives.
  * Overview of mailing lists used by the candidate project.
  * To what extent are external/private mailing lists used?

* Meeting calendars

  * Link to docs about meetings related to the candidate project.
  * Overview of meetings held by the candidate project.
  * To what extent are meetings public, and clearly publicly documented?

* Meeting minutes

  * Link to archives for meeting minutes taken by the candidate project.
  * To what extent are public minutes for meetings taken and shared?

Integrations
============

Details about technical integrations implemented by the candidate project.

* Summarize any existing or planned integrations with other projects.
* Summarize any CI/CD integrations with other projects.
* Summarize any other work that may enable integrations in the future.

  * Continuous Delivery pipelines
  * Configuration management tooling
  * Documentation about cross-project integration
  * APIs for cross-project integration

Vocabulary Reference
--------------------

Explanations of domain-specific vocabulary.

.. todo:: Look into using special rst to make these definitions into tooltips
.. todo:: Consider extracting this to a stand-along file so can reuse elsewhere

* Active

  * In this context, typically related to the activity level of a project or
    person.
  * As a person: "Foo Committer on Bar Project has not sent any patches or done
    any code review for Bar in the last 12 months. Bar's Project Lead reached
    out to Foo Committer to discuss transitioning to an Emeritus Committer."
  * As a project: "Bar Project has not had any non-trivial code changes merged
    in the last 12 months. The LFN TAC reached out to Bar Project to discuss
    transitioning to the LFN Archived lifecycle state."
  * The LFN norm for "active" is about 12 months.

* Committer

  * Person with permission to cause commits to be merged into a project's
    source control repositories.

* Contributor

  * Person who has contributed to a project. "Contributions" are broadly
    defined. Examples include things like code, documentation, and bug tracker
    changes.

* Diverse

  * In this context, typically related to the number of different organizations
    involved in a project.

* Downstream

  * In this context, typically means the products based on a project.
    Community collaborates on upstream project, which is downstreamed by a
    company into a product.
  * Alternatively, could relate to a relationship between two "upstream" open
    source projects (not by-company products) where one consumes (is downstream
    of) the other.
  * As a verb: "to copy something from the open source project to a product
    based on it".
  * As a dependency relationship: "Linux is a downstream of C".

* Upstream

  * In this context, typically means the main open source project a community
    collaborates on. The code, tooling and people that comprise a project.
  * As a verb: "to add something to the main open source project".
  * As a dependency relationship: "C is an upstream of Linux".
