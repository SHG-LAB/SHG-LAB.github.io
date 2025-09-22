---
# Page title
title: Nonlinear Optical Microscopy
date: 2003-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false
share: false
draft: false
# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title:  <h3>Research directions</h3> #<h3>[Направления исследований](/ru/research) </h3>
      subtitle:  1 [Nanoplasmonics](/en/research/plasmonics)  <br> 2 Nonlinear Optical Microscopy <br> 3 [Two-Photon Laser Lithography](/en/research/lithography) <br> 4 [Magneto-Optics](/en/research/magnetooptics)
      text: " 
          # Nonlinear Optical Microscopy 
          
          ### Direction Description

          Confocal linear and nonlinear polarization microscopy is a tool for non-invasive investigation of the spatial distribution of optical properties of various materials and structures. The method is based on probing a sample using focused laser radiation of a certain polarization. A femtosecond parametric light generator is used as the radiation source, providing spectral tunability and high peak intensity necessary for studying the nonlinear properties of materials.
          The confocal microscopy setup allows obtaining high-contrast three-dimensional images by isolating the signal collection region and cutting off the optical response outside the focus of the collecting objective.
          As a result of confocal microscopy, transmission and absorption spectra, luminescence signals, and second- and third-harmonic generation signals are measured, which makes it possible to characterize many properties of microstructures and materials: the magnitude of nonlinear susceptibility, resonator properties, magnetic properties, spectral characteristics, etc.

          ### Laboratory Research Focus

          The main research vector of our laboratory is aimed at studying the nonlinear optical and magneto-optical properties of various samples, as well as the optical characterization of microresonators and other elements of integrated photonics.
          The work is carried out on a custom-built setup that combines confocal microscopy and spectroscopy and is controlled by original software. This approach ensures full control over the measurement process and provides flexibility for modifying the system for non-standard tasks, combining various techniques, and studying a wide range of samples.

          ### Key Achievements

          To date, the following key results have been obtained in this area:

            - Characterization of the magnetic domain structure of ferrite-garnet films; determination of the influence of an applied array of ferromagnetic nanoparticles on it.

            - Characterization of the resonator properties of microcrystals based on organic dyes or polymers (perylene, HDMAC, coumarin, etc.).

            - Investigation of the optical pendulum effect in two-dimensional photonic crystals.

          ### Topics for Course and Diploma Projects

          Students interested in research are offered the following tasks:

            - Study by nonlinear optical microscopy of the distribution of optical radiation in dielectric microresonators.
          
          
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
        tag:
         - Microscopy
         - Microstructures
         
    design:
      view: list
      columns: '2'
---
<!-- Описание навправления для карточки -->

<!-- 1 [Наноплазмоника](/ru/research/plasmonics) <br> 2 [Метаматериалы и фотонные кристаллы](/ru/research/metamaterials) <br> 3 Нелинейная микроскопия <br> 4 [Двухфотонная лазерная литография](/ru/research/lithography) <br> 5 [Магнитооптика](/ru/research/magnetooptics) -->
