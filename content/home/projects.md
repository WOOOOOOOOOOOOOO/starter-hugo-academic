---
widget: slider
weight: 20
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '660px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Neuromorphic Computation
      content: 
        How does owl's brain use combinatorially optimized neural coding 
        to solve np-complete problem? Neural plasticity in spiking neural network
        might have an answer.
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.4
        media: owls.jpg
    - title: Neural Coding for Anxiety
      content: | 
        Can we tell anxious level by deciphering neural activities? 
        Calcium imaging result in mice mPFC showed us some possibilites.
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.4
        media: owls.jpg
    - title: Information Theory Tools for Neuroscience
      content: 
        What's the role of synergistic information in high-dimensional data, and
        how could we estimate it? A practical tool could be established based on 
        partial information decomposition.
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.4
        media: information.jpg
---
