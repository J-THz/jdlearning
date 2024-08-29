---
date: "2023-06-21"

sections:

- block: markdown
  content:
    title:
    subtitle: ""
    text: ''
  design:
    background:
      image: 
        filename: logos.jpg
        size: actual
        position: center
        parallax: false
        text_color_light: true


- block: about.biography
  content:
    title: About me
    username: admin
  id: about

    
- block: collection
  content:
    count: 5
    filters:
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: 'Recent News'
  design:
    columns: "2"
    view: compact
  id: posts

- block: portfolio
  content:
    title: Research Themes
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - project
      tag: ""
    offset: 0
    order: desc
    subtitle: "Our research spans the terahertz (THz) region of the electromagnetic spectrum, situated between the microwave and infrared light, bridging the gap between electronics and photonics. This fascinating frequency range is well worth exploring due to the unique properties of THz radiation and closing this technological gap promises to unlock a variety of groudbreaking solutions for transformative applications."
    text: ""
  design:
    columns: "1"
    view: showcase
  id: projects
  
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
  
- block: collection
  content:
    filters:
      exclude_featured: false
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: compact
    
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent Talks
  design:
    columns: "2"
    view: compact
  id: talks
  
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery  
  gallery_items:
    album:demo
    image:2JD-GB-AT.jpg
    caption:this is my caption
  design:
    columns: "1"
  id: gallery


- block: contact
  content:
    title: Contact
    autolink: true
    email: jd158@uark.edu
    address:
        street: 1 University of Arkansas Fayetteville
        city: Fayetteville
        region: AR
        postcode: '72701'
        country: USA
        country_code: US
    directions: Bell 3183
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/JunliangTHz
      name: Follow Me
    coordinates:
      latitude: '36.06714613121898'
      longitude: '-94.17072305737543'
    
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
