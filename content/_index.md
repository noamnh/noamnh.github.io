---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '🤖 My Work in Robotics'
      text: |-
        I’m a robotics engineer focused on control, manipulation, and planning.  
        I build real-world robotic systems — from low-level firmware to ROS 2 task execution pipelines.

        My research and projects focus on:
        - In-hand manipulation and vibration-based grippers
        - ROS 2 control, FOC motor drivers, and embedded systems
        - Planning frameworks for mobile manipulators
        - Real-time controllers and motion planning

        🚀 I'm always open to collaboration, robotics challenges, or freelance consulting.

  - block: collection
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: card-grid
      columns: 2

  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: all-publications
    content:
      title: All Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation

  - block: markdown
    content:
      title: ☎️ Contact
      text: |-
        You can reach me via [GitHub](https://github.com/noamnh),  
        or email me at **noambotics@gmail.com**  
        I’m always happy to connect with robotics teams and collaborators.
---
