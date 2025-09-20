---
# Page title
title: Two-Photon Laser Lithography
date: 2004-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false
share: false


# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title:  <h3> Research directions </h3> #<h3>[Направления исследований](/ru/research) </h3>
      subtitle:  1 [Nanoplasmonics](/en/research/plasmonics) <br> 2 [Nonlinear Optical Microscopy](/en/research/nlmicroscopy) <br> 3 Two-Photon Laser Lithography <br> 4 [Magneto-Optics](/en/research/magnetooptics) 
      text: "
          <h1> Two-Photon Laser Lithography </h1> 
            
          <h3> Technology Description </h3>

          <p>Two-photon lithography (TPL) is an additive manufacturing method (laser 3D printing) that makes it possible to fabricate three-dimensional micro- and nanoscale structures with complex geometry. The method is based on the nonlinear optical effect of two-photon absorption, which initiates photopolymerization: the initially liquid photoresist solidifies strictly in the focal region of pulsed laser radiation. Subsequent movement of the focus within the material allows layer-by-layer formation of the desired structure. The key advantages of TPL — high spatial resolution (down to 100 nm), the ability to create complex 3D structures, and the functionalization of structures by doping the photoresist — make it a powerful tool for creating integrated photonic devices.</p>

          <h3> Research Focus in the Laboratory </h3>

          <p>The main research direction in our laboratory is aimed at the design, numerical modeling, and experimental fabrication of micro-optical devices for modern optical circuits and fundamental research. The work is carried out on a custom-built lithography setup with original software. This approach provides full control over the printing process and offers flexibility to modify the system for non-standard tasks, different types of substrates, and photoresists.</p>

          <h3> Key Achievements </h3>
          <p>To date, the following key results have been obtained within this area:
          <ol>
          <li>A method has been developed and active microstructures based on polymer doped with laser dye have been fabricated.</li>
          <li>A full technological cycle for fabricating elevated waveguides above the substrate, including input-output radiation devices, has been implemented.</li>
          <li>Optimization of input-outputs devices has been carried out through the use of second-order surfaces, which has improved coupling efficiency.</li>
          </ol>
          </p>

          <h3> Current Tasks and Prospects </h3>
          <p>
          Current tasks of the direction include:
          <ol>
          <li>Developing a printing technology on silicon substrates for direct integration of polymer microstructures with semiconductor photonic chips.</li>
          <li>Design, fabrication, and characterization of complex functional devices based on developed basic elements.</li>
          <li>Exploring new ways of doping the photoresist to obtain devices with special properties.</li>
          </ol>
          </p>

          <h3> Topics for Course and Diploma Projects </h3>

          <p>Students interested in research work are offered the following tasks:

          <ol>
          <li>Design and optimization of integrated photonics elements (waveguides, resonators, splitters) for two-photon lithography using the FDTD (Finite-Difference Time-Domain) method.</li>
          <li>Modeling of resonance and mode characteristics of organic resonator structures of various geometries.</li>
          <li>Fabrication of optical waveguide and resonator structures by TPL and subsequent study of their optical properties.</li>
          </ol>
          </p>

           "
#  цель -- http://localhost:1313/ru/research/
#  http://localhost:1313/content/ru/research/                                
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      gradient_start: '#4bb4e3'
      gradient_end: '#c32b2bff'
    # The gradient angle from 0-360 degrees
      gradient_angle: 180
      # text color (true=light, false=dark, or remove for the dynamic theme color).
      text_color_light: true
    
  - block: collection
    content:
      title: Publications on this topic
      text: 
      count: 999
      filters:
        folders:
          - publication
        publication_type: 
        tag: Lithography
    design:
      view: list
      columns: '2'
---
Описание навправления для карточки


<!-- 
 1 [Наноплазмоника](/en/research/plasmonics) <br> 2 [Метаматериалы и фотонные кристаллы](/en/research/metamaterials) <br> 3 [Нелинейная микроскопия](/ru/research/nlmicroscopy) <br> 4 Двухфотонная лазерная литография <br> 5 [Магнитооптика](/en/research/magnetooptics)  -->