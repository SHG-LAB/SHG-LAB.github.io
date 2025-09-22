---
# Page title
title: Nanoplasmonics 
date: 2001-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false
share: false
# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title:  <h3>Research directions</h3> #<h3>[Направления исследований](/ru/research) </h3>
      subtitle:  1 Nanoplasmonics <br>  2 [Nonlinear Optical Microscopy](/en/research/nlmicroscopy) <br> 3 [Two-Photon Laser Lithography](/en/research/lithography) <br> 4 [Magneto-Optics](/en/research/magnetooptics)
      text: "# Nanoplasmonics  
          
          ### Topic Description

            Nanoplasmonics studies the interaction of light with metallic nanostructures, in which collective oscillations of electrons — plasmons — make it possible to localize the electromagnetic field at scales smaller than the wavelength of light.
            The optical response of such materials is determined not only by the choice of their chemical composition but also by their design and structural geometry.
            All this makes it possible to create media with properties unavailable to conventional optical materials, as well as to resonantly enhance various optical effects.

          ### Laboratory Research Focus

            In our research, special attention is paid to hyperbolic metamaterials (HMMs) — artificial composites consisting of metallic nanorods embedded in a dielectric matrix.
            Such structures possess a number of features: pronounced optical anisotropy, nonlocal optical response, etc. This leads to the emergence of unusual properties of such structures — for example, the existence of the Epsilon-Near-Zero (ENZ) regime, in which one of the main components of the effective permittivity tensor becomes zero.

            Our laboratory has also conducted research on a number of other plasmonic nanostructures, such as magnetoplasmonic crystals, chiral plasmonic structures, and others.

          ### Key Achievements

            To date, the following key results have been obtained in this area:

              1. Active control of the optical response of hybrid structures consisting of HMMs and liquid crystals has been implemented.

              2. Generation of spatial and spatiotemporal optical vortices in HMMs has been demonstrated.

              3. Experimental demonstration of light self-action and enhancement of second-harmonic generation in HMMs due to resonant electric-field enhancement in the spectral vicinity of ENZ.

              4. Enhancement of magneto-optical effects in HMMs has been demonstrated.

              5. Experimental observation of fast- and slow-light effects during the propagation of a laser pulse through HMMs.

            ### Topics for Course and Diploma Projects

            Students interested in research are offered the following tasks:

              1. Plasmonic effects in metamaterials with near-zero permittivity.

              2. Metamaterials with near-zero permittivity: optical properties.
          "
#  цель -- http://localhost:1313/ru/research/
#  http://localhost:1313/content/ru/research/                                
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      gradient_start: '#4bb4e3'
      gradient_end: '#2b94c3'
    # The gradient angle from 0-360 degrees
      gradient_angle: 180
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
      text_color_light: true
  - block: collection
    content:
      title: Publications on this topic
      text: ""
      count: 999
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        tag: Plasmonics
    design:
      view: list
      columns: '2'
---
<!-- Описание навправления для карточки -- вроде бы не видно в полном тексте  -->

<!-- 1 Наноплазмоника <br>  2 [Метаматериалы и фотонные кристаллы](/ru/research/metamaterials) <br> 3 [Нелинейная микроскопия](/ru/research/nlmicroscopy) <br> 4 [Двухфотонная лазерная литография](/ru/research/lithography) <br> 5 [Магнитооптика](/ru/research/magnetooptics) -->

