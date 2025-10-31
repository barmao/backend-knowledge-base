---
name: "📚 Learning Note"
description: "Document something you learned about backend development"
title: "Learn: [Topic Name]"
labels: ["learning", "documentation"]
body:
  - type: textarea
    id: what-learned
    attributes:
      label: "What I Learned"
      description: "Brief description of the concept or technology"
      placeholder: "Example: I learned about Docker volumes for persistent data storage..."
      value: "[Brief description of the concept]"
    validations:
      required: true

  - type: textarea
    id: key-takeaways
    attributes:
      label: "Key Takeaways"
      description: "Main points, insights, or important details"
      placeholder: "- Point 1\n- Point 2\n- Point 3"
      value: "- [Main point 1]\n- [Main point 2]\n- [Main point 3]"
    validations:
      required: true

  - type: textarea
    id: where-fits
    attributes:
      label: "Where This Fits"
      description: "Where should this documentation live?"
      placeholder: "- New file in: `technologies/topic/readme.md`\n- Addition to existing file: `path/to/file.md`"
      value: "- [ ] New file in: `[path]`\n- [ ] Addition to existing file: `[file path]`\n- [ ] Example for: `[concept]`"

  - type: textarea
    id: resources
    attributes:
      label: "Resources I Used"
      description: "Links to docs, articles, videos, or other learning materials"
      placeholder: "- https://example.com\n- https://docs.example.com"
      value: "- [Link 1]\n- [Link 2]"

  - type: dropdown
    id: confidence
    attributes:
      label: "Confidence Level"
      description: "How well do you understand this topic?"
      options:
        - "[ ] Just starting to understand"
        - "[ ] Comfortable with basics"
        - "[ ] Ready to explain to others"
      default: 0
---