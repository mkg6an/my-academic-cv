---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      title: Research Experience
      username: me
    design:
      tag_filter: research  # <--- This is the key "filter" for the profile list
      date_format: "Jan 2006"

  - block: resume-experience
    content:
      title: Teaching Experience
      username: me
    design:
      tag_filter: teaching
      date_format: "Jan 2006"

  - block: resume-experience
    content:
      title: Education
      username: me
    design:
      tag_filter: education # Only shows items in me.yaml tagged 'education'
      date_format: "Jan 2006"
---
