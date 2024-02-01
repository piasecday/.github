name: Help Ticket Template
description: If you need help, fill this ticket and post it to your team repo issue tracker
title: "[Help]: "
labels: ["help"]
projects: ["piasecday/2"]
assignees:
  - benjamsf
body:
  - type: markdown
    attributes:
      value: |
        Mitä apua tarvitset?
  - type: textarea
    id: what-happened
    attributes:
      label: Mitä apua tarvitset?
      description: Kuinka kiire avulla on, mitä koskee? 
    validations:
      required: true
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output, if needed
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell