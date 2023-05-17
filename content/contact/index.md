---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
       If you're interested in the work we do, feel free to check out our GitHub and Twitter to stay up to date with the group's research.  
      # email: test@example.org
      # phone: 888 888 88 88
      address:
        street: 180 Queen's Gate
        city: London
        region: ""
        postcode: 'SW7 2AZ'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '51.499457'
        longitude: '-0.178120'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    social:
      - icon: twitter
        icon_pack: fab
        link: https://twitter.com/GeorgeCushen
      - icon: github
        icon_pack: fab
        link: https://github.com/gcushen
    design:
      columns: '1'
      # background:
      #   image: 
      #     filename: contact.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
