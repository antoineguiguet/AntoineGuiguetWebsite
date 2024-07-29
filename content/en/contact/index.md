---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        You can write your message in this form.
      email: mailto:antoine.guiguet[at]protonmail.com
      address:
        street: Darwinweg 2
        city: Leiden
        postcode: '2333 CR'
        country: The Netherlands
        country_code: NL
      coordinates:
        latitude: '52.164629'
        longitude: '4.472110'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '2'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen
---
