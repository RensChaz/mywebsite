---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - teaching
    title: Teaching
  design:
    columns: "2"
    view: compact
  id: teaching
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Publications and Working Papers
  design:
    columns: "2"
    view: compact
  id: publication
#- block: collection
#  content:
#    count: 5
#    filters:
#      author: ""
#      category: ""
#      exclude_featured: false
#      exclude_future: false
#      exclude_past: false
#      folders:
#      - post
#      publication_type: ""
#      tag: ""
#    offset: 0
#    order: desc
#    subtitle: ""
#    text: ""
#    title: Recent Posts
#  design:
#    columns: "2"
#    view: compact
#  id: posts
#- block: portfolio
#  content:
#    buttons:
#    - name: All
#      tag: '*'
#    - name: Other
#      tag: Demo
#    default_button_index: 0
#    filters:
#      folders:
#      - project
#    title: Projects
#  design:
#    columns: "1"
#    flip_alt_rows: false
#    view: showcase
#  id: projects
# - block: collection
#  content:
#    filters:
#      exclude_featured: true
#      folders:
#      - event
#    title: Recent & Upcoming Talks
#  design:
#    columns: "2"
#    view: compact
#  id: talks
- block: contact
  content:
    address:
      city: Lausanne
      country: Switzerland
      country_code: CH
      postcode: "1015"
      region: 
      street: Odyssea Building, Route Cantonale - Avenue Forel 
    contact_links:
    - icon: linkedin
      icon_pack: fab
      link: https://www.linkedin.com/in/rens-chazottes-659341190/
      name: Rens Chazottes
    email: rens.chazottes@epfl.ch
    subtitle: null
    text: Do you have a question? Do you need further information about a research I am working on? Send me a message!
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
