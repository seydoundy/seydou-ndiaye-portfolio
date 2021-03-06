---
title: Contact
sections:
  - type: hero_section
    title: Contactez-moi
    subtitle: >-
      Pour toutes questions ou informations, n'hésitez pas à me contacter en
      remplissant le formulaire.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ## Pricing

      After a short onboarding call I will be able to provide you with ballpark
      pricing, followed by a detailed proposal once we discuss the details. 

      ### Proposal

      Your proposal will include several choices in terms of pricing structure
      and deliverable timeline.

      ### Terms

      If at any point you'd like to cancel our project, you are required to
      provide a 30-day written notice, after which I will transfer all of your
      assets to you so you can use them anytime.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nom
        label: Nom
        default_value: Votre nom
        is_required: true
      - input_type: email
        label: Email
        default_value: Votre adresse mail
        is_required: true
        name: Email
      - input_type: textarea
        name: message
        label: Votre message
        default_value: Votre message
      - input_type: checkbox
        name: consent
        label: >-
          Je comprends que ce formulaire stocke les informations que j'ai
          soumises afin que je puisse être contacté.
        is_required: true
    submit_label: Envoyer le message
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
layout: advanced
---
