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
  email: gugushviliapp at gmail.com
  address:
    street: Universiteitsingel 40
    city: Maastricht
    region: Limburg
    postcode: '6229 ER'
    country: The Netherlands
    country_code: NL
    

design:
  columns: '2'
---
