---
name: Task
about: Work under the surface that users don't see directly: refactor, maintenance, CI, spike
title: "[task] "
type: Task
labels: []
---

<!-- Examples: turning on a compiler flag, moving CI to a new runner, comparing chart libraries.
When the kind of work is clear, replace [task] in the title with it and add the matching label, the board filters on labels:
[groundwork] [refactor] [maintenance] [testing] [automation] [infrastructure] [spike].
A refactor that changes behaviour is split: a task for the refactor, a feature or bug for the behaviour change. -->

## Goal

<!-- What is wrong or missing today. For a follow-up: the PR, issue or review comment it came out of, and why it was left out there.
Example: "The zone timeline has two owners for play state, so every fix touches two hooks." -->

## Direction

<!-- The intended change, one step per bullet. A sub-bullet carries extra detail or a sub-task of its bullet. For a spike, the question to answer. Example:
- Move play state into the hook that owns the selected date.
  - The slider reads it from there instead of its own ref. -->

## Acceptance criteria

<!-- Refactor: behaviour unchanged, name the areas that must still behave as before. Spike: question answered, follow-ups created. A sub-bullet carries the detail that makes its outcome checkable. Example:
- [ ] One hook owns position and playback
  - The slider and the play button both read from it
- [ ] No visible change in the zone map -->

- [ ]

## Out of scope

<!-- What is deliberately left out, e.g. "Visual changes to the slider". -->

## Links

<!-- Originating PR, related issues, epic. -->
