---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2025-08-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/AcademicCV.pdf
      headings:
        about: 'Bio'
        education: ''
        interests: ''
      show_education: false
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: 'What I work on'
      subtitle: ''
      text: |-
        Making high-fidelity engine combustion simulation both **physically faithful and actually usable**: accurate enough to trust, cheap enough to run inside a real design cycle.

        <div class="hb-cards">

          <div class="hb-card">
            <div class="hb-card-ico">🖥️</div>
            <h3>Making CFD affordable</h3>
            <p>
              Methods that cut the cost of predictive engine CFD: a new
              boundary-condition optimization strategy (<em>Applied Thermal
              Engineering</em>) and a physics-based spark discharge model that
              captures cycle-to-cycle variability without prohibitive cost.
            </p>
          </div>

          <div class="hb-card">
            <div class="hb-card-ico">🔥</div>
            <h3>Combustion of low-carbon fuels</h3>
            <p>
              Chemical mechanism benchmarking, knock and misfire in hydrogen
              engines, and an emerging line extending toward ammonia
              combustion — grounded throughout in high-fidelity simulation and
              experimental validation.
            </p>
          </div>

          <div class="hb-card">
            <div class="hb-card-ico">🔗</div>
            <h3>Engine–system integration</h3>
            <p>
              From the B4IA hydrogen engine conversion to freight-rail and
              techno-economic analysis: connecting engine-scale choices to
              fleet and network performance, a perspective few combustion
              specialists bring.
            </p>
          </div>

        </div>
    design:
      columns: '1'

  - block: markdown
    id: numbers
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="hb-stats">

          <div class="hb-stat">
            <div class="hb-stat-num">51</div>
            <div class="hb-stat-label">Citations</div>
            <div class="hb-stat-sub">h-index = 4 · i10 = 3</div>
          </div>

          <div class="hb-stat">
            <div class="hb-stat-num">140+</div>
            <div class="hb-stat-label">Hours taught</div>
            <div class="hb-stat-sub">MSc Mechanical & Civil Eng.</div>
          </div>

          <div class="hb-stat">
            <div class="hb-stat-num">11</div>
            <div class="hb-stat-label">Papers</div>
            <div class="hb-stat-sub"> 3 more under review</div>
          </div>

        </div>
    design:
      columns: '1'

  - block: markdown
    id: awards
    content:
      title: 'Awards'
      subtitle: ''
      text: |-
        - **4th Italian Cattedra Abertis Award** (2026) — 5000 € for PhD research on sustainable mobility.
        - **First Place, Engineering & Industrial Design**, 19th PACE Forum, Warren, Michigan, USA (2018) — international student team competition.
    design:
      columns: '1'

  - block: markdown
    id: leadership
    content:
      title: 'Leadership & service'
      subtitle: ''
      text: |-
        - **Global Engagement Chair**, ASME DRIVN 2026 conference (Transportation Systems Division) — leading international outreach and institutional partnerships.
        - **Vice Chair**, ASME Italy Section.
        - **Peer reviewer** for *Energies* (MDPI) and for the IEEE ITS, AIIT TIS and SAE Torino conferences.
        - **Mentee**, Young ISSNAF Mentoring Program, connecting Italian researchers with senior scientists in North America.

        <p class="text-sm text-gray-500 mt-2"><a href="/leadership/">See full leadership &amp; service →</a></p>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured publications
      text: 'A selection. See the [full publication list](/publications/).'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
      show_read_time: false
      show_date: false

  - block: markdown
    id: statement
    content:
      title: 'Personal statement'
      subtitle: ''
      text: |-
        My research keeps moving **deeper into combustion science** — toward a
        more fundamental understanding of how turbulence, chemistry, and heat
        transfer govern the combustion of low-carbon and carbon-free fuels,
        including an emerging line on ammonia. My aim is to build models that
        are both physically sound and usable in real design workflows, and to
        derive reduced-order models from high-fidelity CFD and experimental data
        that can inform engine control and calibration.

        I am equally drawn to **combustion as a phenomenon in its own right**,
        beyond any single application. I would value the chance to complement my
        simulation background with experimental combustion research, working
        closer to optical diagnostics and measurement, to ground my models in
        observed physics and strengthen the loop between simulation and
        experiment. I am also open to data-driven and machine-learning methods
        where they accelerate combustion modeling and design.

        My work is naturally **collaborative** and sits at the intersection of
        engine development, transport operations, and energy-systems analysis. I
        have co-supervised master's theses across energy, mechanical, civil, and
        aeronautical engineering, and I believe diversity of perspectives is
        fundamental to solving complex problems in engineering and
        sustainability.

        When I'm not surrounded by computational models, you will usually find
        me **outdoors** — running, hiking, or on a court — or somewhere with a
        camera in hand. These things keep my perspective balanced and remind me
        that the technologies I model on a screen ultimately serve real people,
        communities, and environments.

        If you'd like to talk about combustion, CFD, sustainable transport, or a
        possible collaboration, feel free to [get in touch](mailto:simona.gurri@polito.it).
    design:
      columns: '1'
---
