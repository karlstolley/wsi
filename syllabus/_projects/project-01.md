---
title: Shaping a Web System
due_date: &deadline 2020-01-23
goals:
  - The first goal.
  - The second goal.
  - The third goal.
requirements:
  -
deliverables:
  - action: Post draft deliverables to Basecamp.
    description: "Your draft post should include:"
    details:
      -
    deadline: 2020-01-19
  - action: Post final deliverables to Basecamp.
    description: Thing one.
    details:
      -
    deadline: *deadline
---

For this project, you will apply the techniques and advice in [<cite>Shape
Up</cite>](https://basecamp.com/shapeup) to shape and pitch a web system that integrates with other
systems that are part of a business, governmental, or non-profit organization. In other words, what
you’re shaping is **not** a complete, self-contained application (Facebook, for a bad example) but a
system that fits into some broader, larger set of systems that makes up a business’s concerns. As a
starting point, think about systems for billing, shipping, account management, internal
communication, issue tracking, customer support, ticket- or seat-booking, and so on.

The system you shape will have two core public components: a web-based user interface for managing
and interacting with the system itself, and a data API for integrating with other systems within
(and potentially outside) and organization.

Internally, your system will have or rely upon at least three components: a structured data store,
consumption of a free (if rate-limited) relevant API providing supplemental data, and a server-side
web framework for responding to incoming requests for both your system's web-based user interface
and its public data API. It is not necessary (or even desirable) to determine the specific details
of those components at the shaping phase, although you absolutely must make sure a public data API
is available to provide the supplemental data your system will ingest.

**ITMD 467 students** will deliver a shaped X system.

**ITMD 567 students** will research, invent, or discover some kind of business-oriented system and
then deliver it as a shaped system and pitch.
