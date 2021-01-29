---
name: Team Meeting Items 
about: Used for gathering items for our team meeting with a new issue every week.
title: "Weekly Team meeting: {{ date | date('add', 5, 'days') | date('Fr') }}"
labels:
  - "teammeeting"
---
### Friday, {{ date | date('MMM Do') }}
