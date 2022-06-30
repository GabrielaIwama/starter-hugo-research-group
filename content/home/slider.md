---
widget: slider
weight: 40
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title:
      content:
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.8
        media: group-picture-ice-cream.jpg
        fit: cover
    - title:
      content:
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.8
        media: group-picture-stocherkahn.jpg
        fit: contain
    - title:
      content:
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.8
        media: group-picture-christmas.jpg
        fit: cover
---
