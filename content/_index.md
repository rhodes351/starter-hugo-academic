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
       My research asks how social policies and institutions shape economic inequality, with a focus on labor markets and credit, wealth, and debt. My research has been published in American Sociological Review, Social Forces, Social Problems,
       and Nature Human Behaviour.

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
