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
       My research asks how power and policies shape economic inequality. One strand of research focuses on labor market inequality and the returns to worker power in the United 
       States. Another strand of research considers the institutional and relational sources of disparities in credit, debt, wealth, and financial markets. My published work 
       appears in Rural Sociology, The Sociological Quarterly, and Social Science & Medicine, among other outlets.

  - block: collection
    id: research
    content:
      title: Current Research Projects
      text:
      filters:
        folders:
          - post
      sort_by: 'Title'
      sort_ascending: false
---
