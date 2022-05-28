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
  email: 859311743@qq.com
  phone: + (86)13161082860
  address:
    street: No.28 of Xianning West Road
    city: Xi'an
    region: Shaanxi
    postcode: '710049'
    country: CHINA
    country_code: CN
  directions: ''
  contact_links:
    - icon: qq
      icon_pack: fab
      name: Q Me
      link: 'https://im.qq.com/index'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
