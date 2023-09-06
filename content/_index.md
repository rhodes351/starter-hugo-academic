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
       Much of my current research asks how power and policies shape economic inequality. One strand of research focuses on labor market inequality and the returns to worker 
       power in the United States. Another strand of research considers the institutional and relational sources of disparities in credt, debt, and financial markets.

  - block: collection
    id: research
    content:
      title: Current Research Projects
      text:
      filters:
        folders:
          - post
---
