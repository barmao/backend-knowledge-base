---
name: "🧪 Test Simple Template"
description: "Test the template system"
title: "Test: [Topic]"
labels: ["test"]
body:
  - type: textarea
    id: description
    attributes:
      label: "Test Description"
      description: "This should be pre-filled when you create the issue"
      value: "## This is a test\n\nIf you can see this text pre-filled, the template system is working correctly!\n\n- [ ] Item 1\n- [ ] Item 2\n- [ ] Item 3"
    validations:
      required: true
---