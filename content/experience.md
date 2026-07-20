---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  # - block: resume-experience
  #   content:
  #     title: Education
  #     username: me
  #     filters:
  #       tags: ['none'] # This tags filter usually only hits EXPERIENCE, leaving Education untouched
  # - block: resume-experience
  #   content:
  #     username: me
  #     title: 'Research Experience'
  #     # If your template supports tag filters in this block:
  #     filters:
  #      tag: ['Research'] 

  # content/_index.md (inside the sections array)

# Stack 1: Research
  - block: collection
    content:
      title: Research Experience
      username: me
      filters:
        tags: [research] # Only shows items tagged 'research'
    design:
      view: resume-experience

# Stack 2: Teaching
  - block: collection
    content:
      title: Teaching Experience
      username: me
      filters:
        tags: [research] # Only shows items tagged 'research'
    design:
      view: resume-experience

  # Stack 3: Education
  - block: collection
    content:
      title: Education
      username: me
      filters:
        folders: [education]
    design:
      view: resume-experience
---
