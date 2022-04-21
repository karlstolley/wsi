---
title: Web System Public-Release Sprint
due_date: &deadline 2022-05-05
preview: false
goals:
  - Quickly revise a system’s core functionality and features to ready an initial public release.
  - Monitor your system in production.
requirements:
  - >
    Tag significant public releases, including release candidates, according to the [Semantic
    Versioning specification](https://semver.org)
  - >
    Your system **must** be deployed to a publicly available server, if you’ve not already done so.
  - >
    Your deployment strategy **must** include the ability to roll back to an earlier, known stable
    version.
  - >
    Once deployed, your system **must** be monitored by some type of lightweight monitoring software
    or process manager, such as [PM2](https://pm2.keymetrics.io/). Ideally, monitoring
    will be integrated to the extent possible with your deployment automation.
deliverables:
  -
    action: Post your final public release project to Basecamp.
    description: >
      Provide a team-authored report of your progress and challenges during the short public-release
      cycle. Note the challenges you had operating on a much shorter development cycle, and preview
      the work your team would do next, were the project to live on beyond the current semester.
    deadline: *deadline
  -
    action: Email self and group-member critique memo to the instructor.
    description: >
      Write at least 5–7 sentences assessing your own work on the project this semester, and for
      each group member a 3–5-sentence assessment. Optionally, if you have suggestions for the
      instructor on how to improve this class in the future, please include those as well.
    deadline: *deadline
---

Due to the semester’s time constraints (and an imagined impatient manager), this final cycle will
deviate from the measured cycles for your system’s alpha and beta releases, and instead focus on a
ten-day sprint to ship a `1.x.x` version for public release.

<!--
  - >
    Learn to automate deployment using a method like CI or CD to safeguard its uptime and
    availability.

  - >
    Once deployed, your system **must** implement some type of continuous integration, continuous
    delivery, or continuous deployment method to safeguard and automate your deployment.
-->
