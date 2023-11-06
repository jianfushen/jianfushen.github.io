---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about


- block: collection
  id: publication
  content:
  # Choose how many pages you would like to display (0 = all pages)
    count: 4
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Recent Publications
  design:
    columns: "2"
    view: citation  

- block: collection
  id: workingpaper
  content:
  # Choose how many pages you would like to display (0 = all pages)
    count: 4
    filters:
      exclude_featured: true
      folders:
      - workingpaper
    title: Working paper
  design:
    columns: "2"
    view: citation  

- block: collection
  id: conferencepaper
  content:
  # Choose how many pages you would like to display (0 = all pages)
    count: 4
    filters:
      exclude_featured: true
      folders:
      - conferencepaper
    title: Conference paper
  design:
    columns: "2"
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
  
# - block: collection
#   content:
#     # Choose how many pages you would like to display (0 = all pages)
#     count: 3
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - news
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: News
#   design:
#     columns: "2"
#     view: compact
#   id: news

# - block: collection
#   content:
#     # Choose how many pages you would like to display (0 = all pages)
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - posts
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts

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

