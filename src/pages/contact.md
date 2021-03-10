---
title: Contact
sections:
  - type: hero_section
    title: Kontakt aufnehmen
    subtitle: Ausfüllen und wir kommen zeitnah auf Sie zu
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: |
      ## Geräte

      Lorem Ipsum

      ### Preis

      Lorem Ipsum

      ### Konditionen

      Lorem Ipsum
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Ihre email
        is_required: true
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht
      - input_type: checkbox
        name: consent
        label: Ich stimme den Datenschutzbestimmungen zu.
        is_required: true
    submit_label: Senden
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Contact
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
template: advanced
---
