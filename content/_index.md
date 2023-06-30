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

- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Institut National de la Recherche Scientifique (INRS)
      company_logo: org-1
      company_url: "https://inrs.ca/en/"
      date_end: ""
      date_start: "2020-04-01"
      description: |2-
          * Advisor: [Prof. Roberto Morandotti](https://inrs.ca/en/research/professors/roberto-morandotti/)
          * Managing all research activities related to THz photonics in the [Nonlinear Photonics Group](https://www.nonlinearphotonics.com/).
          * Funding: [NSERC](https://www.nserc-crsng.gc.ca/index_eng.asp) Discovery, Strategic, and Alliance programs; New Frontiers in Research Fund ([NFRF](https://www.sshrc-crsh.gc.ca/funding-financement/nfrf-fnfr/index-eng.aspx)); FRQ [Audace](https://frq.gouv.qc.ca/recherche-intersectorielle/programme-audace/).
      location: Montreal, Canada
      
      title: Group leader
    - company: Institut National de la Recherche Scientifique (INRS)
      company_logo: org-1
      company_url: "https://inrs.ca/en/"
      date_end: "2020-03-01"
      date_start: "2017-08-01"
      description: |2-
          * Advisor: [Prof. Roberto Morandotti](https://inrs.ca/en/research/professors/roberto-morandotti/)
          * Single-shot ultrafast THz photography for capturing transient events.
          * Waveguide-integrated signal-processing devices for THz communications. 
          * THz biomedical imaging for nanoparticle-assisted laser therapeutics.
          * Funding: [Mitacs](https://www.mitacs.ca/en) Elevate Postdoctoral Fellowship.
      location: Montreal, Canada
      title: Postdoctoral Research Fellow
    - company: Georgia Tech - CNRS, International Research Lab (IRL) 2958
      company_logo: org-gt
      company_url: "https://www.gatech.edu/"
      date_end: "2017-07-01"
      date_start: "2014-04-01"
      description: |2-
          * Advisor: [Prof. David S. Citrin](https://ece.gatech.edu/directory/david-s-citrin) and [Dr. Alexandre Locquet](http://photonics.georgiatech-metz.fr/node/25)
          * THz imaging for nondestructive evaluation of fiber-reinforced composites.
          * THz applications in cultural heritage science: examination of art and archaeology.
          * Advanced THz deconvolution techniques for depth resolution enhancement.
          * Funding: Conseil Regional du Grand Est of the Fonds European de Developpement Regional ([FEDER](https://www.europe-en-france.gouv.fr/fr/fonds-europeens/fonds-europeen-de-developpement-regional-FEDER)) and the [Institut Carnot ARTS](https://www.ic-arts.eu/).
      location: Atlanta, USA/Metz, France
      title: Graduate Research Assistant
    - company: Georgia Tech - CNRS, International Research Lab (IRL) 2958
      company_logo: org-gt
      company_url: "https://www.gatech.edu/"
      date_end: "2017-07-01"
      date_start: "2016-01-01"
      description: |2-
          * Advisor: [Prof. David S. Citrin](https://ece.gatech.edu/directory/david-s-citrin) and [Dr. Alexandre Locquet](http://photonics.georgiatech-metz.fr/node/25)
          * THz imaging for the non-invasive and non-contact characterization of failure modes and corrosion process in polyer-coated steel.
          * Funding: [ArcelorMittal](https://corporate.arcelormittal.com/), the World's Leading Integrated Steel and Mining Company.
      location: Atlanta, USA/Metz, France
      title: Graduate Research Assistant
    - company: Department of Automation, Tsinghua University
      company_logo: org-ts
      company_url: "https://www.tsinghua.edu.cn/en/"
      date_end: "2011-07-01"
      date_start: "2008-08-01"
      description: |2-
          * Advisor: Prof. Li Cao
          * Novel measurment strategies for key physical parameters of gas/liquid in industrial pipelines.
          * Funding: National Natural Science Foundation of China and Tokyo Keiso Co. Ltd, Japan.
      location: Beijing, China
      title: Graduate Research Assistant
    - company: Department of Automation, Tsinghua University
      company_logo: org-ts
      company_url: "https://www.tsinghua.edu.cn/en/"
      date_end: "2008-07-01"
      date_start: "2007-08-01"
      description: |2-
          * Advisor: Prof. Yong Zhao
          * Research on optical fiber sensing system based on magnetic fluid.
          * Funding: National Natural Science Foundation of China.
      location: Beijing, China
      title: Undergraduate Research Assistant
    title: Experience
    
  design:
    columns: "2"
  id: experience  
    
    
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: "Our Research News Releases in Media"
    text: ""
    title: 'Recent Posts'
  design:
    columns: "1"
    view: showcase
  id: posts
  
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
    email: Junliang.Dong@inrs.ca
    address:
        street: 1650 Boul. Lionel Boulet
        city: Varennes
        region: QC
        postcode: 'J3X 1P7'
        country: Canada
        country_code: CA
    directions: Office 109
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/JunliangTHz
      name: Follow Me
    coordinates:
      latitude: '45.630015909254425'
      longitude: '-73.3831983349873'
    
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
