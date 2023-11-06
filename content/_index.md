---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      username: admin

  - block: collection
    id: publication
    content:
      title: Research
      # Choose how many pages you would like to display (0 = all pages)
        count: 4
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: portfolio
      content:
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      buttons:
      - name: All
        tag: '*'
      - name: United International College
        tag: UIC
      - name: The Hong Kong Polytechnic University
        tag: PolyU
      default_button_index: 0
      filters:
        folders:
        - teaching
      title: Teaching
    design:
      columns: "2"
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    id: teaching


  - block: contact
    content:
      title: Contact
      address:
        city: Zhuhai
        country: China
        street: United International College(UIC), 2000 Jintong Road, Tangjiawan, Zhuhai, Guangdong Province, China
      email: kwokyuenfan@uic.edu.cn
    design:
      columns: "2"
    id: contact

title: null
type: landing
---
