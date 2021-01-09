---
title: Bizimle İletişime Geçin ...
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: İletişime Geçmek İçin Aşağıdaki Boşlukları Doldurun .
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: İsim
        default_value: ''
        is_required: true
      - input_type: email
        name: email
        label: e-Posta
        default_value: ''
        is_required: true
      - input_type: select
        name: ''
        label: Konu
        default_value: ''
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mesaj
        default_value: ''
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: gönder
template: advanced
---
