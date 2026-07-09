---
name: Daily Digest
on:
  schedule: daily on weekdays
  workflow_dispatch:
permissions:
  contents: read
safe-outputs:
  create-issue:
    max: 1
---

# daily-digest

Every weekday morning, create a GitHub issue that summarizes all open
issues and pull requests in this repository. Group them by label
(issues without labels go in an "Untriaged" section). For each item
include the title, the author, and how long it has been open. Start
with a one-paragraph summary of the overall state of the repo.
Title the issue "Daily Digest – <date>".


