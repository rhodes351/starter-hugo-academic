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
      title: My Research
      image:
       filename: image2.jpg
      text: My research asks how social institutions and policies shape inequality, poverty and social mobility. One strand focuses on worker power and labor market inequality. Another   
       strand examines the causes and consequences of household credit, wealth, and debt. Click on the links below to learn more about some of my recent projects...

  - block: collection
    id: research
    content:
      title:
      text:
      filters:
        folders:
          - post
      sort_by: 'Title'
      sort_ascending: false
---
