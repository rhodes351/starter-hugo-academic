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
       My research asks how power and policy shapes economic inequality. One strand of research focuses on labor markets and the returns to worker power. Another   
       strand examines the institutional and relational sources of inequalities in credit markets. My published work has appeared in Social Forces, Social Problems,
       and Nature Human Behaviour, among other outlets.

  - block: collection
    id: research
    content:
      title: Research Projects
      text:
      filters:
        folders:
          - post
      sort_by: 'Title'
      sort_ascending: false
---
