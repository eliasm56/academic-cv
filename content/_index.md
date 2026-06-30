---
title: Elias Manos — Academic Portfolio
summary: "Welcome to the academic portfolio of Elias Manos, showcasing biography, publications, employment timeline, education, and CV."
date: 2026-06-30
type: landing
design:
  spacing: 6rem
sections:
  - block: hero
    content:
        eyebrow: Academic Researcher
        title: Elias Manos
        text: "Graduate student at the University of Connecticut in Natural Resources & the Environment. Focused on Arctic permafrost and remote sensing applications."
        primary_action:
          url: /publications/
          text: View Publications
          icon: academicons/orcid
          style: gradient
        secondary_action:
          url: /cv/
          text: View CV
          icon: hero/document-text
          style: ghost
    design:
        background:
          color:
            light: "#ffffff"
            dark: "#0b1021"
          gradient:
            type: radial
            start: primary-500
            end: transparent
            position: "50% -10%"
            shape: ellipse
            size: "80% 80%"
        text_color_light: true
        gradient_mesh:
          enable: true
          style: orbs
          colors:
            - primary-500/20
            - secondary-500/20
          orb_count: 2
          positions:
            - top-0 left-1/4
            - bottom-0 right-1/4
          sizes:
            - w-96 h-96
            - w-80 h-80
          animation: pulse
          intensity: medium
  - block: resume-biography
    content:
        username: me
        text: "Graduate student at the University of Connecticut. Research focuses on Arctic permafrost processes, remote sensing, and AI applications to environmental science."
        button:
          url: /cv/
          text: Download CV
    design:
        avatar:
          size: xl
          shape: circle
  - block: markdown
    content:
        text:
          |
            ## Employment
            
            - Graduate student, Natural Resources & the Environment, University of Connecticut, Storrs, US
            
            ## Education
            
            - Doctor of Philosophy, Natural Resources & the Environment, University of Connecticut, Storrs, US (2024–present)
            - Master of Science, Natural Resources & the Environment, University of Connecticut, Storrs, US (2022–2024)
            - Bachelor of Arts, Geography, University of Connecticut, Storrs, US (2018–2022)
  - block: collection
    content:
        title: Publications
        collection: publication
        limit: 10
  - block: markdown
    content:
        text:
          |
            ## Curriculum Vitae
            
            Download my CV [here](/cv.pdf).
---
