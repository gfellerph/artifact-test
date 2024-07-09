---
name: Component v2
about: Component v2 description
title: ''
labels: enhancement
assignees: ''

---

name: Component v2
description: Add a working item for a component targeted at the new Design v2
title: ""
labels: ["bug"]
projects: ["swisspost/3"]
assignees:
body:
  - type: markdown
    attributes:
      value: |
        Short component description
  - type: input
    id: designurl
    attributes:
      label: Design
      description: Link to the component in Figma
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Short description
      description: A short description of the component, disambiguation if needed
      placeholder: A tooltip shows short, additional information on focusable elements.
    validations:
      required: false
  - type: checkboxes
    id: tokens
    attributes:
      label: Tokens are ready
      description: Indicates whether tokens already exist for this component
