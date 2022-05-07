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
  #form:
  #  provider: netlify
  #  formspree:
  #    id:
  #  netlify:
  #    # Enable CAPTCHA challenge to reduce spam?
  #    captcha: false

  # Contact details (edit or remove options as required)
  email: <my 1st name (starts with e)> <dot> <my last name (starts with v)> @inserm.fr
  #phone: 888 888 88 88
  address:
    street: Faculté de Médecine de Sorbonne Université, 27, rue Chaligny
    city: Paris
    #region: HT
    postcode: '75012'
    country: France
    country_code: FR
  coordinates:
    latitude: '48.849'
    longitude: '2.384'
  directions: Floor 8, office 814
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me (but if you send me an email I'll likely be more responsive)
      link: 'https://twitter.com/eugeValdano'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
