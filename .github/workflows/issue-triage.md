---
name: Issue Triage
on:
  issues:
    types: [opened]
  reaction: "eyes"
permissions:
  contents: read
safe-outputs:
  add-labels:
    max: 3
  add-comment:
    max: 1
---

# issue-triage

When a new issue is opened in this repository, triage it:
1) Classify it as one of: bug, enhancement, question, documentation.
2) Add the matching label.
3) Post a friendly comment that: greets the author by username,
   summarizes your understanding of the issue in one or two sentences,
   and — if it is a bug report missing reproduction steps, expected
   behavior, or environment details — politely asks for the missing
   information.
Keep the comment short and helpful. Do not close or edit the issue. Add an "eyes" (👀) reaction to the issue so the author knows it was seen.