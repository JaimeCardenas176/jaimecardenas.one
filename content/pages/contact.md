---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Para ponerte en contactco conmigo por favor rellena el formulario
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: nombre
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: asunto
        label: Asunto
        default_value: Please select
        options:
          - Error en la página web
          - Sponsor
          - Otros
      - input_type: textarea
        name: mensaje
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mis datos para contactarme posteriormente.
    submit_label: Enviar mensaje
seo:
  title: Contact0
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
