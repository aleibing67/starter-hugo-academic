---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: aleibing@diw.de
  phone: +49 30 89789 256
  address:
    street: Mohrenstraße 58
    city: Berlin
    region: Berlin
    postcode: '10117'
    country: Germany
    country_code: GER
  coordinates:
    latitude: '52.5122'
    longitude: '13.3887'


design:
  columns: '2'
---
