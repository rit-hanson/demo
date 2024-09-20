name: Bug Report
description: Report incorrect behavior in the airflow library
title: "BUG: "
labels: [bug]

body:
  - type: textarea
    id: problem
    attributes:
      label: Issue Description
      description: >
        Please provide a description of the issue and the screenshot of the error message
        and related dag/task.
    validations:
      required: true
  - type: textarea
    id: expected-behavior
    attributes:
      label: Expected Behavior
      description: >
        Please describe or show a code example of the expected behavior.
    validations:
      required: true