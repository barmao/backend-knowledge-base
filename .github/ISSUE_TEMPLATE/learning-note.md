---
name: "📚 Learning Note"
description: "Document something you learned about backend development"
title: "Learn: [Topic Name]"
labels: ["learning", "documentation"]
body:
  - type: textarea
    id: content
    attributes:
      label: "Learning Content"
      description: "Fill out your learning notes below"
      placeholder: |
        ## What I Learned
        [Brief description of the concept]

        ## Key Takeaways
        - [Main point 1]
        - [Main point 2] 
        - [Main point 3]

        ## Where This Fits
        - New file in: `[path]`
        - Addition to existing file: `[file path]`

        ## Resources I Used
        - [Link 1]
        - [Link 2]

        ## Confidence Level
        - [ ] Just starting to understand
        - [ ] Comfortable with basics
        - [ ] Ready to explain to others
    validations:
      required: true
---