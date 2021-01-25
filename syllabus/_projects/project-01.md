---
title: Shaping a Web System
due_date: &deadline 2021-02-04
preview: false
goals:
  - >
    Improve your ability to use rough sketches and brief, clear writing to describe and pitch a
    system design
  - >
    Increase your skill in writing in [GitHub-flavored Markdown
    syntax](https://github.github.com/gfm/)
  - Practice scoping and reducing a system to its core, essential components
requirements:
  - >
    Refer to [the two example pitches](https://basecamp.com/shapeup/1.5-chapter-06#examples) in
    <cite>Shape Up</cite> to help guide your own work, especially at the draft stage
deliverables:
  - action: Post draft deliverables to Basecamp.
    description: "Your draft post should include:"
    details:
      - >
        Your name and Project Pitch as the post title (e.g., `Scarlet Hawk: Project Pitch`)
      - >
        A link to a GitHub Gist with ideas of your Problem, Appetite, Solution, along with any clear
        Rabbit Holes and No Goes
      - >
        Fat-marker sketches, diagrams, and illustrations embedded in your GitHub Gist.
      - >
        Specific requests for feedback from the instructor and peers. Write this in the body of your
        Basecamp post
    deadline: 2021-01-28
  - action: Schedule a one-on-one consultation with the instructor.
    description: >
      Sometime by the end of the day on Monday, February 1, you will have a one-on-on consultation
      with the instructor about your project draft. Watch for scheduling details on Basecamp.
    deadline: 2021-01-28
  - action: Respond to at least 3 of your peers' Draft Projects
    deadline: 2021-02-01
  - action: Post final deliverables to Basecamp.
    description: "Your final-deliverable post must include:"
    details:
      - >
        A link to a GitHub Gist of your written pitch, illustrated with fat-marker diagrams and
        sketches, outlining Problem, Appetite, Solution, Rabbit Holes, and No Goes.
      - >
        A self-assessment, written in the text of the Basecamp post, of 250 words or so of your work
        on this project and your degree of confidence and satisfaction with your final pitch.
    deadline: *deadline
---

For this project, you will apply the approach and techniques outlined in [<cite>Shape
Up</cite>](https://basecamp.com/shapeup) to shape and pitch a web system that integrates with other
systems that are part of a business, governmental, or non-profit organization. In other words, what
you’re shaping is **not** a complete, self-contained application (Facebook, for a bad example) but a
system that fits into some broader, larger set of systems that makes up a business’s concerns. As a
starting point, think about systems for billing, shipping, account management, internal
communication, issue tracking, customer support, ticket- or seat-booking, and so on.

The system you shape will have two core public components: a web-based user interface for managing
and interacting with the system itself, and a data API for integrating with other systems within
(and potentially outside) an organization.

Internally, your system will have or rely upon at least three components: a structured data store,
consumption of a free (if rate-limited) relevant API providing supplemental data, and a server-side
web framework for responding to incoming requests for both your system's web-based user interface
and its public data API. It is not necessary (or even desirable) to determine the specific details
of those components at the shaping phase, although you absolutely must make sure a public data API
is available to provide the supplemental data your system will ingest.

**ITMD 467 students** will deliver the pitch for a shaped system for Chicago residents to submit
complaints to their correct ward alderman, drawing on data from the [City of Chicago Data
Portal](https://data.cityofchicago.org/) to determine a resident’s alderman, and perhaps to enhance
the contents of complaint data. For example, a complaint about rats might reference or include data
from the city's
[311 Service Requests API](https://data.cityofchicago.org/Service-Requests/311-Service-Requests/v6vf-nfxy)
dataset. Your system will need to deliver its own database for tracking residents and their
complaints, and the alderman's response to or resolution of the complaint.

**ITMD 567 students** will research, invent, or discover some kind of business-oriented system and
then deliver it as a shaped system and pitch. If public data is available, but not in API form, you
can pitch a data-scraping setup as part of your system.
