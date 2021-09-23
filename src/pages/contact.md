---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: "Let’s build something great together.\n\nComplete my contact form or send me an email at Contact (at) K3mal.com\n\n***\n\n## Location\n\n### Seattle, WA & REMOTE \U0001F30D\n"
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Work
          - Consulting
          - General
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Kemal D - Contact
  description: Get In Touch.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Kemal D - Contact
      keyName: property
    - name: 'og:description'
      value: Get In Touch.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Kemal D - Contact
    - name: 'twitter:description'
      value: Get In Touch.
    - name: 'og:image'
      value: images/cta-about.svg
      keyName: property
      relativeUrl: true
template: advanced
---
