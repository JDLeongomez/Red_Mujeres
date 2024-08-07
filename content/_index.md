---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
      image:
        filename: Logo_Red.jpg
      text: |
        <br>
        
        La **Asociación Red de Mujeres Víctimas y Profesionales** (**R.M.V.P.**) es una organización de mujeres víctimas de Violencia Sexual, defensora de los Derechos Humanos, que promueve el empoderamiento de las víctimas de este delito en el marco del conflicto armado y fuera de él.

  - block: markdown
    content:
      title: Nuestra Historia
      subtitle: ''
      text: |
        
        <div class="container-wrapper-genially" style="position: relative; min-height: 400px; max-width: 100%;"><video class="loader-genially" autoplay="autoplay" loop="loop" playsinline="playsInline" muted="muted" style="position: absolute;top: 45%;left: 50%;transform: translate(-50%, -50%);width: 80px;height: 80px;margin-bottom: 10%"><source src="https://static.genial.ly/resources/panel-loader-low.mp4" type="video/mp4" />Your browser does not support the video tag.</video><div id="5f577a3e08563f0d8a876510" class="genially-embed" style="margin: 0px auto; position: relative; height: auto; width: 100%;"></div></div><script>(function (d) { var js, id = "genially-embed-js", ref = d.getElementsByTagName("script")[0]; if (d.getElementById(id)) { return; } js = d.createElement("script"); js.id = id; js.async = true; js.src = "https://view.genial.ly/static/embed/embed.js"; ref.parentNode.insertBefore(js, ref); }(document));</script>
  
  - block: slider
    content:
      slides:
      - title: Historias de vida
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000
  
  - block: collection
    content:
      title: Curso
      text: ""
      count: 5
      filters:
        folders:
          - publication
#        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: contact
    id: contacto
    content:
      title: Contacto
      text: |-
        Para información general del grupo, por favor contactar a {{% mention "juan-david-leongomez" %}}. Para información específica, contacta directamente al [investigador o investigadora](../people/) que necesites.
      email: jleongomez@unbosque.edu.co
      phone: (+57) 601-6489000 Ext. 1901
      address:
        street: Av. Cra. 9 No. 131 A - 02
        city: Bogotá
        region: Distrito Capital
        postcode: '110121'
        country: Colombia
        country_code: CO
      coordinates:
        latitude: '4.710263'
        longitude: '-74.030982'
      directions: Busca los laboratorios de Psicología, en el edificio I
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ1Q4rEtBU-OaEP8C56LfqyMcMpEl-P-_PQi6ZX8kRaK60xAzrpCKBAK6ynvv2_MinKvhOSwHSaf'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: false
    
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '1'
---
