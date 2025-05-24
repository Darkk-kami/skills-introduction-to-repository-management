name: Feature Request
about: Suggest a new feature for this project
title: "[Feature]: "
labels: "enhancement"
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        ## 👋 Thanks for taking the time to fill out a feature request!

  - type: input
    id: summary
    attributes:
      label: Feature Summary
      description: Briefly describe the feature you're requesting.
      placeholder: "Add email notifications for order updates"
    validations:
      required: true

  - type: textarea
    id: problem
    attributes:
      label: Problem or Opportunity
      description: What problem does this solve or what opportunity does it create?
      placeholder: "Users currently don't know when an order is updated unless they refresh the dashboard..."
    validations:
      required: true

  - type: textarea
    id: solution
    attributes:
      label: Proposed Solution
      description: Describe your ideal solution.
      placeholder: "Use WebSockets for real-time notifications, and fallback to email if offline..."
    validations:
      required: true

  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
      description: Have you considered any alternative solutions or features?
      placeholder: "We considered polling the server, but it's inefficient and introduces latency..."
    validations:
      required: false

  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Add any other context, links, or screenshots.
      placeholder: "Mockup links, diagrams, references..."
    validations:
      required: false
