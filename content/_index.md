---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: hero
    content:
     image:
       filename: image2.jpg
     text: |-
       My research asks how power and policy shapes inequality. One strand of research focuses on labor market inequality and the returns to worker power. Another   
       strand considers the institutional and relational sources of disparities in financial markets. My published work has appeared in Social Problems,
       Nature Human Behavior, and Journal of Health and Social Behavior, among other outlets.

  - block: collection
    id: research
    content:
      title: Recent Research Projects
      text:
      filters:
        folders:
          - post
      sort_by: 'Title'
      sort_ascending: false
---
