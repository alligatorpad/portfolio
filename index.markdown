---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#layout: home
layout: splash

defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true

  # _experience
  - scope:
      path: "experience"
      type: experience
    values:
      layout: "experience"
      author_profile: false
      share: true

---
