---
title: Web System Beta-Release Cycle
due_date: &deadline 2020-04-23
preview: false
goals:
  - Analyze complex computing problems and apply principles of computing and other relevant
    disciplines to identify solutions
  - Assist in the creation, execution, and ongoing revision of an effective project plan
  - Design, implement, and evaluate a computing-based solution to meet a given set of computing
    requirements
  - Communicate effectively in a variety of professional contexts
  - Function effectively as a member or leader of a team engaged in activities appropriate to
    web-systems integration tasks
  - Identify and analyze user needs and take them into account in the selection, creation, evaluation
    and administration of computer-based systems
  - Apply security principles and practices to maintain operations in the presence of risks and
    threats
requirements:
  - >
    You and your team **must** actively use some kind of communication hub for coordinating team
    work and communication (e.g., Slack, Discord, or a team-members-only Basecamp). It is up to your
    team whether to invite the instructor to participate. But that might be a good idea.
  - >
    You and your team **must** use GitHub issue-tracking and code-reviews via pull requests to
    coordinate your team’s work and project progress.
  - >
    You and your team **must** tag significant alpha releases according to the [Semantic Versioning
    specification](https://semver.org).
  - >
    You and your team **must** publish release notes on GitHub to accompany all tagged releases,
    even at the alpha stage.
  - >
    You and your team **must** write documentation for your system, both as a standalone file, such
    as a `README.md`, and as code-adjacent comments. You are encouraged to explore your options for
    generating documentation from inlined comments for the language you’re  using (for example,
    [JSDoc](https://jsdoc.app/about-getting-started.html) is a documentation generator for
    JavaScript).
  - >
    Your system **must** ingest data from one or more third-party sources: either a data API or data
    that you scrape, maintain, and prepare in an API-like way.
  - >
    Your system **must** implement at least one appropriate datastore. It’s possible that some parts
    of your system might rely on a database, and others on flat files, a hashed document store, or
    some other mechanism that persists data in the event of system restarts or crashes.
  - >
    Your system **must** deliver error-free, standards-compliant HTML, CSS, and JavaScript to the
    browser. Your HTML **must** be valid and semantic; your CSS **must** be written in standalone
    stylesheets and rely on intelligent approaches to feature detection; and your JavaScript
    **must** be unobtrusive (that is, written leveraging event handlers and wholly avoiding
    deprecated JavaScript attributes in your HTML, such as `onload`).
  - >
    Your system’s front end **must** deliver its core functionality to the browser even in the
    absence of JavaScript or CSS. CSS, JavaScript, and advanced front-end techniques—such as
    asynchronous requests, service workers, and web sockets—**must** be implemented in a
    progressively enhanced way.
  - >
    Your system **must** provide a well-structured data API in an appropriate, error-free
    data-serialization format, such as JSON or XML, and it **must** feature sensible,
    developer-friendly data and endpoints. You and your team **should** include coverage of your
    API in your documentation.
  - >
    Your system **must** include functional, unit, and integration tests on the back end, as
    appropriate, and visual regression-testing on the front end (e.g.,
    [BackstopJS](https://github.com/garris/BackstopJS)).
  - >
    Your system **must** limit its reliance on massive, all-in-one frameworks. You may choose either
    a front- or back-end framework, but not both. For example, if you opt to use Bootstrap (which,
    yuck), you will have to craft the back end of your system yourself. Choose wisely.
  - >
    Your system **should** include one or more appropriate, leading-edge front-end development APIs.
    Options include local storage, service workers, web sockets, or any combination of elements that
    make up [progressive web app
    architectures](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/App_structure).
  - >
    Your system **should** judiciously include feature-specific libraries, modules, or other
    packaged dependencies. Challenge yourselves as a group to develop the feature from scratch first
    (that is, using your language's built-in APIs and standard library), and decide later whether to
    incur the technical debt and inherent risks of third-party dependencies. Consider also the
    technical debt and inherent risks of developing your own feature, of course.
  - >
    Your system **should** support multiple runtime environments (e.g., development, staging,
    testing, production). Your system’s configuration **must** be readily shareable among members of
    your team. A system that tucks its configuration into a MySQL database, as WordPress does
    (which, yuck), is almost certainly a non-starter.
  - >
    Once deployed, your system **must** implement some type of continuous integration, continuous
    delivery, or continuous deployment method to safeguard and automate your deployment.
  - >
    Once deployed, your system **must** be monitored by some type of lightweight monitoring software
    or process manager, such as [PM2](https://pm2.keymetrics.io/). Ideally, monitoring
    will be integrated to the extent possible with your deployment automation.

deliverables:
  -
    action: "Due **weekly**: Post team progress reports weekly on the class Basecamp."
    description: >
      Aim to do these on Thursdays. Rotate responsibility among your team members for the weekly
      writeup of your progress and struggles. Reference your project’s repositories, commits, and
      release notes by URL as appropriate.
  -
    action: Schedule a mid-cycle conference with the instructor.
    description: >
      Sometime during the week of April 6, you and your team will have a virtual chat of about
      thirty minutes with the instructor. Watch for scheduling details on Basecamp.
    deadline: 2020-04-02
  -
    action: Post your final beta release project to Basecamp.
    description: >
      Provide a team-authored report of your progress and challenges during the beta cycle. Note
      the number and frequency of beta releases you made during the cycle, and preview the work
      your team anticipates for the upcoming public-release sprint.
    deadline: *deadline
  -
    action: Email self and group-member critique memo to the instructor.
    description: >
      Write at least 5–7 sentences assessing your own work on the project so far, and for each group
      member a 3–5-sentence assessment.
    deadline: *deadline
---

In this second of two cycles, you and your team will push your system beyond its alpha stages to
achieve greater stability and test coverage along with some kind of build pipeline and
continuous-integration approach to produce and deploy a series of `0.x.x-beta.x` releases.

Plan to include unit, functional, and integration test coverage as early in your process as
possible. In fact, aim for 100% test coverage of your existing, alpha code before you move on to any
other plans for your beta iterations.

Note that the requirements listed with this project are the overall system requirements for the
final version to be delivered on Thursday, May 7. By the end of the beta cycle, you should have met
all of these requirements. Be sure to take stock of them early in this cycle, and contact the
instructor immediately if you’re concerned about any of them.
