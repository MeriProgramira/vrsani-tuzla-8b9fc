---
title: Ostanimo u kontaktu
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Ime
    default_value: Vaše ime
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Vaša email adresa
    is_required: true
  - input_type: select
    name: predmet poruke
    label: predmet poruke
    default_value: Molimo odaberite
    options:
      - Greška na stranici
      - Spon
      - Other
  - input_type: textarea
    name: message
    label: Poruka
    default_value: Vaša poruka
  - input_type: checkbox
    name: consent
    label: Razumijem da se informacije date u formi čuvaju u svrhu kontakta.
submit_label: Pošalji poruku
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
template: contact
---
molimo Vas da popunite formu 
