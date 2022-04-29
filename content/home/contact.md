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
  email: d.w.owen@liverpool.ac.uk
  phone: 07475909943
  address:
    street: 1st Floor Roxby Building
    city: Liverpool
    region: Merseyside
    postcode: 'L69 7ZT'
    country: United Kingdom
    country_code: UK
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM me
      link: 'https://twitter.com/Twitter'
    
design:
  columns: '2'
---
