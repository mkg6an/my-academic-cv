---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    content:
      title: Research Experience
      filters:
        folders: [experience]
        tags: [research]
    design:
      view: resume-experience
      date_format: "Jan 2006"
  - block: collection
    content:
      title: Teaching Experience
      filters:
        folders: [experience]
        tags: [teaching]
    design:
      view: resume-experience
      date_format: "Jan 2006"
---
