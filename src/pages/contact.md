---
title: Contact
sections:
  - type: section_contact
    template: section_contact
    section_id: contact
    title: 'I hope we can keep in touch :)'
    content: "I'm looking for new opportunities! If you are interested in my works or blog posts, please contact me at\_[kangyeon.lee.alicia@gmail.com](mailto:example@example.com)\n"
    background: gray
    form_id: contactForm
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: NAME
        is_required: true
        default_value: Your name
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: EMAIL
        is_required: true
        default_value: Your email
      - type: form_field
        template: form_field
        input_type: select
        name: subject
        label: SUBJECT
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
          - '0': l
            '1': o
            '2': r
            '3': e
            '4': m
            '5': '-'
            '6': i
            '7': p
            '8': s
            '9': u
            '10': m
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: landing
---
