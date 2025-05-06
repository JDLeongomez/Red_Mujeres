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

  - block: slider
    content:
      slides:
      - title: Fragmentos
        content: 'Una obra de arte viva,<br>un lugar de memoria,<br>un espacio de creación artística'
        align: left
        background:
          image:
            filename: fragmentos.jpg
            filters:
              brightness: 0.5
          position: left
          color: '#666'
        link:
          icon: youtube
          icon_pack: fab
          text: Ver video
          url: https://www.youtube.com/watch?v=d7rAb2O0JV8&ab_channel=MuseoNacionaldeColombia
      - title: Nosotras
        content: 'Nuestras acciones'
        align: right
        background:
          image:
            filename: victimas.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#666'
        link:
          icon: youtube
          icon_pack: fab
          text: Ver video
          url: https://www.youtube.com/watch?v=a11xuWAsebk&t=7s&ab_channel=ConcéntrikaMedios
      - title: Nuestros eventos
        content: ''
        align: right
        background:
          image:
            filename: evento-central.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: youtube
          icon_pack: fab
          text: Ver video
          url: https://www.youtube.com/watch?v=6kVsN_vYudE&ab_channel=UniversidadCentral%2CBogotá%2CColombia
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000

#  - block: markdown
#    content:
#      title: Nuestra Historia
#      subtitle: ''
#      text: |
#        
#        <div class="container-wrapper-genially" style="position: relative; min-height: 400px; max-width: 100%;"><video class="loader-genially" autoplay="autoplay" loop="loop" playsinline="playsInline" muted="muted" style="position: absolute;top: 45%;left: 50%;transform: translate(-50%, -50%);width: 80px;height: 80px;margin-bottom: 10%"><source src="https://static.genial.ly/resources/panel-loader-low.mp4" type="video/mp4" />Your browser does not support the video tag.</video><div id="5f577a3e08563f0d8a876510" class="genially-embed" style="margin: 0px auto; position: relative; height: auto; width: 100%;"></div></div><script>(function (d) { var js, id = "genially-embed-js", ref = d.getElementsByTagName("script")[0]; if (d.getElementById(id)) { return; } js = d.createElement("script"); js.id = id; js.async = true; js.src = "https://view.genial.ly/static/embed/embed.js"; ref.parentNode.insertBefore(js, ref); }(document));</script>
  
#  - block: collection
#    content:
#      title: Curso
#      text: ""
#      count: 5
#      filters:
#        folders:
#          - publication
#        publication_type: 'article'
#    design:
#      view: citation
#      columns: '1'

  - block: contact
    id: contacto
    content:
      title: Contacto
      text: |-
        Para información general por favor contactar a {{% mention "angela-maria-escobar" %}}.
      email: coordinacion@redmujeresvisiblemente.org
      phone: (+57) 312 200 4935
      address:
        street: 
        city: 
        region: 
        postcode: 
        country: 
        country_code: CO
      coordinates:
        latitude: 
        longitude: 
      directions: 
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # appointment_url:
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
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
