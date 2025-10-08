name: User Story
description: Create a new user story
title: "[Story] "
labels: ["story"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        Use the format: "As a [role], I need [feature] so that [benefit]."
  - type: input
    id: story
    attributes:
      label: User Story
      placeholder: "As a..."
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance Criteria
      description: Use Gherkin syntax: Given… When… Then…
