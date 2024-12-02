
---
title: Our Team
summary: Meet the amazing team behind our success
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: podium
    id: main_team
    content:
      title: Our Leadership Team
      description: Meet the key members driving our vision and success.
      members:
        - name: Alice Johnson
          position: CEO
          image: /images/alice.jpg
          link: alice-johnson/
        - name: Bob Smith
          position: CTO
          image: /images/bob.jpg
          link: bob-smith/
        - name: Clara Davis
          position: COO
          image: /images/clara.jpg
          link: clara-davis/
      design:
        type: podium

  - block: collection
    id: all_team
    content:
      title: All Team Members
      filters:
        folders:
          - team
      design:
        view: list
        columns: 1
---
