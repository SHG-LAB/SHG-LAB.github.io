---
# Page title
title: Magneto-Optics 
date: 2005-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false
share: false
# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title:  <h3>Research directions </h3> #<h3>[Направления исследований](/ru/research) </h3>
      subtitle:  1 [Nanoplasmonics](/en/research/plasmonics) <br> 2 [Nonlinear Optical Microscopy](/en/research/nlmicroscopy) <br> 3 [Two-Photon Laser Lithography](/en/research/lithography) <br> 4 Magneto-Optics
      text: "
          <h1> Magneto-Optics and Generation of Magnetically Induced Second Harmonic </h1>
                      
          <h3> Description of the Field </h3>

          <p>Magneto-optics is a branch of optics that studies a wide class of effects of static magnetization on the parameters of light reflected from or transmitted through a structure. Depending on the geometry of the experiment (mutual orientation of the structure, direction of the external magnetic field, and the light wave vector), magneto-optical effects can manifest as modulation of the intensity or rotation of the polarization plane of optical radiation.</p>
                    
          <p>It is known that under the action of intense laser radiation on nonlinear crystals, as well as on surfaces and interfaces, generation of light at twice the pump frequency — second harmonic generation — can be observed. In the case of magnetic media, the parameters of such a response (magnetically induced second harmonic generation) can also depend on the orientation and magnitude of the material’s magnetization.</p>

          <p>The magnitudes of magneto-optical effects in second harmonic generation are generally 1–2 orders higher than their linear analogues. At the same time, while the source of linear magneto-optical response is the “volume” of the magnetic medium within the light penetration depth, magnetically induced second harmonic generation occurs mainly at surfaces and interfaces. Thus, by combining linear and nonlinear magneto-optical methods, one can study in detail the magnetic properties of media at the micro- and macro-level — visualize domains, study the distribution of magnetic moments and magnetic ordering, determine the directions of easy magnetization axes, and investigate the properties of nanostructures and hidden interfaces.</p>

          <p>The interaction of laser radiation with magnetic media is a rapidly developing research area, associated with advances in modern technologies for fabricating structures with fundamentally new magnetic and optical properties unattainable in natural materials. On the other hand, in nanophotonics there is an urgent task of developing methods for efficient control of light parameters, including by applying a magnetic field — in this regard, it is important to search for methods to enhance magneto-optical effects, for example, by exciting resonances of various natures in a magnetic structure.</p>

          <h3> Research Focus in the Laboratory </h3>

          <p>The main research direction in our laboratory is the study of magnetic and magneto-optical properties of structures of various designs with inhomogeneous magnetization distribution — microstructures with magnetic vortices, multilayer magnetic nanofilms, ferromagnetic metasurfaces, and others. An important direction also remains the study of composite magnetic materials that combine ferromagnetic properties with plasmonic effects or hyperbolic dispersion regimes. The work is carried out on experimental setups of our own design with software developed in the laboratory, which allows research to be adapted to specific objects and scientific tasks.</p>

          <h3> Key Achievements </h3>
          <p>To date, the following key results have been obtained in this area:
          <ol>
          <li>It has been experimentally shown that in composite nanostructures of ferromagnetic and noble metals, the excitation of localized surface plasmons, lattice plasmon resonances, and propagating plasmon-polaritons leads to an enhancement of magneto-optical and magnetic nonlinear-optical responses.</li>

          <li>In composite hyperbolic metamaterials, enhancement of magneto-optical effects is realized in the spectral region where the real part of the effective component of the dielectric permittivity approaches zero (epsilon-near-zero, ENZ).</li>

          <li>A nonlinear optical method has been proposed for detecting the macroscopic toroidal magnetization moment in microstructures with magnetic vortices.</li>

          <li>It has been shown that second harmonic microscopy allows visualization of surface domains in films of the ferromagnetic dielectric garnet-ferrite.</li>
          </ol> </p>

          <h3> Current Tasks and Prospects </h3>

          <p>Current tasks of the field include:
          <ol>
          <li>Searching for methods to pin (fix) the walls of stripe and cylindrical magnetic domains in garnet-ferrite by applying a magnetic lattice to its surface.</li>
          <li>Developing methods of magnetic control of transmission coefficient in an ENZ metamaterial based on gold nanorods in a dielectric matrix and a nickel film.</li>
          </ol> </p>

          <h3> Topics for Course and Diploma Projects </h3>

          <p>Students interested in research work are offered the following tasks:

          <ol>
          <li> Pinning of the magnetic domain structure in garnet films with a magnetic metasurface  
          </li>
          <li> Magneto-optical effects in garnet-ferrite films with a magnetic lattice on their surface  </li>
          </ol> </p>

          
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
          - Magnetism
          - Magnetooptics
          
    design:
      view: list #compact #list #citation
      columns: '2'
---
<!-- Описание навправления для карточки  -->

<!-- 1 [Наноплазмоника](/ru/research/plasmonics) <br> 2 [Метаматериалы и фотонные кристаллы](/ru/research/metamaterials) <br> 3 [Нелинейная микроскопия](/ru/research/nlmicroscopy) <br> 4 [Двухфотонная лазерная литография](/ru/research/lithography) <br> 5 Магнитооптика -->
