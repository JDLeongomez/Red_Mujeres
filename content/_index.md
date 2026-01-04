---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    design:
      columns: '1'
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="hero-custom">
          <div class="hero-text">
            <p>
              La <strong>Asociación Red de Mujeres Víctimas y Profesionales</strong>
              (<strong>R.M.V.P.</strong>) es una organización de mujeres víctimas de
              Violencia Sexual, defensora de los Derechos Humanos, que promueve el
              empoderamiento de las víctimas de este delito en el marco del
              conflicto armado y fuera de él.
            </p>
          </div>
          <div class="hero-media">
            <div class="iframe-wrapper">
              <iframe
                title="Collage Red"
                src="https://view.genially.com/69599a30af1831ae6ec403e2"
                allowfullscreen
                loading="lazy"
              ></iframe>
            </div>
          </div>
        </div>

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
      - title: Para nosotras, pero con nosotras
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
#        <div style="width: 100%;"><div style="position: relative; padding-bottom: 56.25%; padding-top: 0; height: 0;"><iframe title="Cronologia Red de Mujeres Víctimas y Profesionales" frameborder="0" width="1200" height="675" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://view.genially.com/695161378a83802e6cbdfcc9" type="text/html" allowscriptaccess="always" allowfullscreen="true" scrolling="yes" allownetworking="all"></iframe> </div> </div>
  
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

  - block: markdown
    content:
      title: Nos han apoyado
      subtitle: ''
      text: |
        <div class="supporters-grid">
          <a href="https://www.gov.uk/world/organisations/british-embassy-colombia.es-419" target="_blank" rel="noopener">
            <img src="/media/logos/british-embassy-col.png" alt="British Embassy Colombia">
          </a>
          <a href="https://www.iom.int/es" target="_blank" rel="noopener">
            <img src="/media/logos/oim.png" alt="OIM">
          </a>
          <a href="https://www.diaconia.bo" target="_blank" rel="noopener">
            <img src="/media/logos/diaconia.png" alt="Diaconía IFD">
          </a>
          <a href="https://minciencias.gov.co" target="_blank" rel="noopener">
            <img src="/media/logos/minciencias.png" alt="Minciecnias">
          </a>
          <a href="https://www.mukwegefoundation.org" target="_blank" rel="noopener">
            <img src="/media/logos/mukwege-foundation.png" alt="Mukwege Foundation">
          </a>
          <a href="https://www.oxfamcolombia.org" target="_blank" rel="noopener">
            <img src="/media/logos/oxfam.png" alt="Oxfam">
          </a>
        </div>
        
  - block: contact
    id: contacto
    content:
      title: Contacto
#      text: |-
#        Para información general por favor contactar a Angela Maria Escobar.
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
      contact_links:
        - icon: instagram
          icon_pack: fab
          name: Instagram
          link: 'https://discourse.gohugo.io'
        - icon: facebook
          icon_pack: fab
          name: Facebook
          link: 'https://www.facebook.com/RedMujeresVP'
    
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
