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
       filename: <div style="display: flex; justify-content: space-between;">
                 {{< figure src="/media/image2.jpg" width="48%" >}}
                 {{< figure src="/media/image3.jpg" width="48%" >}}
                 </div>
     text:

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
