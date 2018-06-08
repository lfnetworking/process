*******************************************
Linux Foundation Networking Fund Principles
*******************************************

LFN (Linux Foundation Networking Fund) is the shared home of previously
independent communities with different backgrounds and histories. Each
community has valuable lessons and practices to share with the others. The goal
of this document is to find consensus on a common set of principles based on
these experiences, to better forge a healthy community and meet the needs of
all projects within LFN. This is a living document that future TACs should
improve on.

Autonomy of Projects
====================

Each LFN project is a self-governing community that is responsible for the
project and creates its value. Each project knows best how to accomplish its
mission, and can do so best by being supported but largely left to act
autonomously.

Each LFN project has a governing body such as a TSC. The role of LFN is to
support projects' governing structures, not to burden them with excessive
governance. When at all possible, decisions should be made by projects
themselves, not the LFN.

Because we give projects lots of responsibility, and support them from LFN's
finite resources, we have high expectations for projects. When we consider
accepting new LFN projects, we want to be sure that they have a healthy
community and are on the right track for success.

Contribute Upstream
===================

Organizations that get value from projects should give back to the upstream
projects they get value from. Organizations that take without giving put the
long-term sustainability of the project at risk.

Ultimately, contributions take the form of human time. Organizations that get
value from projects should contribute human time upstream, either directly via
upstream contributions or indirectly by paying other organizations that
contribute upstream.

Cross-Project Integration
=========================

A major advantage of LFN is the cross-project collaboration it enables. From
a technical standpoint, cross-project integration is a key element of enabling
cross-project collaboration.

Cross-project integration may take the form of Continuous Integration/
Continuous Delivery pipelines connecting projects. These provide well-tested,
recommended ways to deploy integrated projects, both in test and production
environments. CI/CD pipelines can also enable quick feedback for developers
about how changes in one project impact other projects, enabling quick, easy
cross-project development.

LFN should encourage projects to develop cross-project integrations.

Diversity of Committers
=======================

The diversity of projects' committers is important for projects' health.
Projects should strive to develop a set of committers from various
organizations, not dominated by a single entity. Preventing a project from
being dominated by a single interest gives confidence that contributions will
be welcomed even if they do not align with the priorities of a dominant
interest. This is a key element of ensuring stable long term growth of projects
and attracting contributions.

Diversity of Contributors
=========================

Thriving Open Source projects should have contributors from a diverse set of
organizations. This prevents domination by a single entity, results in projects
that can be more easily extended as they are not designed from a single
viewpoint, encourages following an upstream-first development model and gives
downstream users confidence that they can work with a project, not just a
company.

Listen to Users
===============

A project's user base is key to its success. LFN should encourage projects to
proactively develop their user base and take user feedback, especially from
users with real deployments, seriously.

Users of LFN projects should contribute to LFN projects by giving feedback,
sharing what they have learned, and clearly explaining their challenges.

Marketplace of Ideas
====================

The goal of the Linux Foundation Networking Community is to promote development
and adoption of the Open Source Networking ecosystem. The ecosystem will take
the form of a marketplace of ideas, not a single reference implementation. It
is not our job to select one solution or one single stack.

This principle does not suggest that we should be entirely laissez faire. Doing
so can be wasteful of community resources, counter productive and may result in
multiple poor quality solutions. It does mean that we do not automatically
reject projects because they are overlapping or competing when different design
choices or market segments are being explored or addressed.

Open Governance
===============

Open Source projects should be governed openly. Governance policies should be
clearly defined and publicly, prominently available. Governance systems should
be designed in the open, with input open to everyone.

Although it is typically not possible to start an open source project using
community-elected governance, as there is not a community to elect leaders
from, projects should transition to a community-elected model as soon as
possible.

Open Source Tooling
===================

Open Source projects are only as Open Source as the tooling required to develop
the project. Using non-Open Source tooling makes Open Source projects less
Open Source. LFN should encourage projects to depend only on Open Source
tooling whenever possible.

In some cases, the productivity increase from using non-Open Source tooling may
justify the loss of openness incurred. However, the choice to use non-Open
tooling should not be made lightly, and the loss of openness incurred should be
taken into account.

In all cases and at all times choice of tooling belongs to the projects. At no
time may choice of tooling be forced from outside the projects.

Projects First and Only
=======================

Supporting the projects within LFN is LFN's primary concern. Supporting
projects to achieve their goals is the best way to support Open Source
Networking and the networking industry.

Projects are the entities that get things done in LFN. Whenever possible, work
should be done within projects, not LFN. LFN itself should remain a lightweight
layer for collaboration among a set of projects. LFN may organize committees or
working groups to facilitate collaboration.

Public Tooling
==============

All tooling should be public and accessible to anyone. Additionally, the public
tooling should be the primary tooling used for development.

Examples of tooling that should be public:

* Bug tracker
* Chat tooling
* Code repository
* Code review
* Continuous Integration tooling
* Documentation
* Mailing list
* Meeting calendars
* Meeting minutes

Upstream-First
==============

Open Source projects typically work best when contributions are driven in the
upstream project, using upstream discussion channels to build consensus and
upstream code review tooling to iterate on proposals.

The inverse, developing changes downstream and then "throwing them over the
wall" to the upstream community, is typically fraught with problems. Diverse
stakeholders in upstream communities typically bring viewpoints that result
in changes that are more generically applicable, do not assume the specifics
of the downstream's implementation. Maintaining downstream-only changes can
result in costly rebases to consume new upstream changes, or falling behind
upstream. Working upstream enables a culture of "collaborate on building
together", which is materially better than "build things in silos and
collaborate on combining them".

On rare occasions it may be acceptable to develop code downstream and then
push it upstream. For example, many new projects are seeded with ideas that
started downstream.

Specific upstream-first practices include:

* Upstream code review is the primary forum for developing code, giving
  feedback. Patches almost always require iterative feedback/fix cycles.
  Large patches in particular often require input from many people over a long
  period before they are ready to be merged. Large patches merged without
  iterative feedback, especially by people from the same company, will raise
  red flags.
* Large features should be planned publicly, with community input.
