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
      email: mailto:antoine.guiguet[at]mnhn.fr
      address:
        street: 45 rue Buffon
        city: Paris
        postcode: '75005'
        country: France
        country_code: FR
      coordinates:
        latitude: '48.841824'
        longitude: '2.359262'
    
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
