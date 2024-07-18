name: Bug report
description: Create a report to help us improve
labels:
  - bug
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please give a clear and concise description of the bug
    validations:
      required: true
  - type: textarea
    id: reproduction
    attributes:
      label: Reproduce
      description: A minimal script to reproduce the issue is the most efficient way to have your bug addressed and fixed very quickly
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected behavior
      description: What is the expected behavior?
