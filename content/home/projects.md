---
widget: slider
weight: 10
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '660px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Information Theory Tools for Neuroscience
      content: 
        What is the role of synergistic information in high-dimensional data, and
        how could we estimate it? A practical tool can be established based on 
        partial information decomposition.
      align: left
      background:
        position: center
        color: '#333'
        brightness: 1.0
        media: information.jpg
    - title: Neural Coding for Anxiety
      content: | 
        Can we decipher how anxiety levels are represented in neural activities? 
        In collaboration with Garima Shah,
        analysis of calcium imaging data from mice reveals to us some possibilites.
      align: center
      background:
        position: right
        color: '#666'
        brightness: 1.0
        media: anxiety.jpg
    - title: Neuromorphic Computation
      content: 
        How does the brain create combinatorially optimized coding for selective attention? 
        Neural plasticity in spiking neural network
        may have an answer to this np-complete problem.
      align: right
      background:
        position: center
        color: '#555'
        brightness: 1.0
        media: owls.jpg

    
---
