---
title: Home
sections:
  - type: hero_section
    title: Uwe Kaißer
    actions:
      - label: Kontakt
        url: /contact
        style: primary
    image: images/benjamin-combs-wuU_SSxDeS0-unsplash.jpg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    subtitle: Dienstleistungen rund um den Grünen Bereich
    content: >
      Bei uns sind alle Leistungen individuell auf Ihre Wünsche und Ihren Garten
      abgestimmt.
  - type: features_section
    title: Unsere Services
    subtitle: Garten- und Landschaftsbauarbeiten
    features:
      - title: Garten Pflegearbeiten
        subtitle: Schöne Grünflächen und Gärten wollen gepflegt werden.
        content: >
          Nur so haben Sie lange Freude daran. Unser kompetentes Team übernimmt
          gerne sämtliche Pflegearbeiten Ihrer Grünanlage. 
        actions:
          - label: Beispiele
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/pflegearbeiten.jpeg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Baumpflege
        subtitle: Haarschnitt für Ihren Baum
        content: |
          Lorem Ipsum
        actions:
          - label: Mehr
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/friendly-tortoise.jpeg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Neuanpflanzung
        subtitle: Neue Pflanzen und Bäume
        content: >
          Unsere Auftraggeber sind in der Regel Kommunen, Hausverwaltungen,
          Wohnbaugesellschaften, Unternehmen oder Privatpersonen. Wir erledigen
          die Schneeräumarbeiten schnell und zuverlässig.
        actions:
          - label: Mehr
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/Logo_kaisser.jpeg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Beratung und Planung
    align: center
    grid_items:
      - image: images/gruen-teck-beratung_planung-X47JQZ-L-182.jpeg
        image_alt: Logo 2
        image_align: center
      - title_align: left
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        type: grid_item
        image: images/GBO_web_01.jpeg
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: grid_section
    title: Referenzen
    subtitle: Was unsere Kunden über uns denken
    grid_items:
      - content: |
          Wir waren super zufrieden und würden jedem den Service empfehlen!

          **Max Mustermann,** *32*
        image: images/person_round.png
        image_position: left
        image_width: twenty-five
      - content: |
          Wir waren super zufrieden und würden jedem den Service empfehlen!

          **Max Mustermann,** *32*
        image: images/magical-owl.png
        image_position: left
        image_width: twenty-five
      - content: |
          Wir waren super zufrieden und würden jedem den Service empfehlen!

          **Max Mustermann,** *32*
        image: images/person_round.png
        image_position: left
        image_width: twenty-five
      - content: |
          Wir waren super zufrieden und würden jedem den Service empfehlen!

          **Max Mustermann,** *32*
        image: images/person_round.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: |
      ## Kontakt aufnehmen

      Einfach anrufen via 11111111111

      oder hier unsere Kontaktformular nutzen
    content_align: left
    form_position: right
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
        label: Einverstanden mit Datenschutzvereinbarung.
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
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
template: advanced
---
