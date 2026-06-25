---
name: Feature request
about: A new detection rule, a config option, or another improvement
title: ""
labels: enhancement
assignees: ""
---

## The problem

<!-- What kind of false-positive Robot test is escaping today, or what friction you hit. -->

## Proposed rule or change

<!-- For a NEW detection rule: show the bad pattern it should catch, and a
legitimate look-alike it must NOT catch. State whether it should block (HIGH) or
only warn (LOW). Remember: HIGH must almost never fire on legitimate tests. -->

```robotframework
*** Test Cases ***
Bad Pattern
    # should be flagged

Legitimate Look Alike
    # must stay clean
```

## Alternatives considered

<!-- Existing tools (Robocop, RFLint) that already cover this? -->
