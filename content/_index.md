---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-07-10
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About Me'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: 'Research Summary'
      subtitle: ''
      text: |-
        My disseration work focuses on design considerations and causal inference methods for challenging longitudinal studies. Specifically, I have worked on problems complicated by small sample sizes, estimands that are difficult to define, and complex treatment patterns and structures. My first dissertation project discusses appropriate statistical methods for comparing survival outcomes under two different schedules of the same repeated treatment, such as annual versus biennial mammography screening, within the target trial emulation framework. Currently, I am developing a methodological framework for learning tailored multi-component interventions with applications to implementation science and health policy. 
        
        My other ongoing and past projects include collaborative studies in areas such as nephrology and perinatal health. I have worked directly with clinicians, biologists, and epidemiologists in my past positions, and have experience translating statistical methods and study results for various audiences. During my PhD program, I have had the opporunity to present original research at both clinical and statistical conferences. I love research, and aim to continue innovating statistical methods motivated by and implemented in collaborative projects throughout my career. 
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: cta-card
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
        css_style: ''
---
