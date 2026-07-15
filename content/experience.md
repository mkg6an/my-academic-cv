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
      title: Education
      username: me
      filters:
        tags: ['none'] # This tags filter usually only hits EXPERIENCE, leaving Education untouched
  - block: resume-experience
    content:
      username: me
      title: Research Experience
      # If your template supports tag filters in this block:
      filters:
       tag: ['research'] 
  - block: resume-experience
    content:
      title: Teaching Experience
      username: me
      is_education_first: false
      filters:
       tag: ['teaching']
---
