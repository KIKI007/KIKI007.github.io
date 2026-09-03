---
layout: page
title: ISD Seminar 2026 Fall
description: Postgraduate Seminars
img: assets/img/course/isd.jpg
importance: 1
category: work
related_publications: true
---

<link rel="stylesheet" href="{{ '/assets/css/seminar-gallery.css' | relative_url }}">

<!-- =========================================================
     ISD SEMINAR 2026 FALL
     ========================================================= -->

<p class="lead">
  The ISD Seminar Series brings together interdisciplinary researchers to present their latest work, exchange ideas, and discuss emerging research topics. This year, the seminar series is co-hosted by Prof. Qijia Shao and Ziqi Wang.
</p>

<p>
  Click a seminar title in the schedule below to jump directly to its details.
</p>


<!-- =========================================================
     SEMINAR SCHEDULE / TABLE OF CONTENTS
     ========================================================= -->

<h2 id="schedule">Seminar Schedule</h2>

<div class="table-responsive">
  <table class="table table-hover">
    <thead>
      <tr>
        <th style="width: 15%;">Date</th>
        <th style="width: 15%;">Time</th>
        <th style="width: 10%;">Location</th>
        <th style="width: 15%;">Speaker</th>
        <th style="width: 15%;">Host</th>
        <th>Talk</th>
      </tr>
    </thead>

    <tbody>

      <tr>
        <td>September 21</td>
        <td>13:30–14:30</td>
        <td>Rm 4621</td>
        <td>Prof. SHI, Fan (NUS)</td>
        <td>Prof. Ziqi Wang</td>
        <td>
          <a href="#shi-fan">
            Simulation Is Back: Scaling Contact-Rich, Long-Horizon Manipulation
          </a>
        </td>
      </tr>

      <tr>
        <td>September 28</td>
        <td>13:30–14:30</td>
        <td>Rm 4621</td>
        <td>Prof. LEUNG, Pok Yin Victor (CityU)</td>
        <td>Prof. Ziqi Wang</td>
        <td>
          <a href="#victor">
            My journey from architectural design to digital fabrication to construction robotics and beyond.
          </a>
        </td>
      </tr>
    </tbody>
  </table>
</div>


<!-- =========================================================
     TALK 1
     ========================================================= -->

<hr class="my-5">

<section id="shi-fan" class="seminar-talk">

  <h2>
    Simulation Is Back: Scaling Contact-Rich, Long-Horizon Manipulation
  </h2>

  <!-- Speaker + basic information -->
  <div class="row align-items-start mt-4">

    <div class="col-md-3 mb-4">
      {% include figure.liquid
        loading="eager"
        path="assets/img/course/seminar2026/shifan/shifan.png"
        title="Professor SHI, Fan"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

    <div class="col-md-9">

      <h3>Prof. SHI, Fan</h3>

      <p class="text-muted">
        Department of Electrical and Computer Engineering<br>
        National University of Singapore
      </p>

      <p>
        <strong>Date:</strong> September 21<br>
        <strong>Time:</strong> 13:30–14:30<br>
        <strong>Location:</strong> Rm 4621
      </p>

    </div>

  </div>


  <!-- Speaker biography -->
  <h4 class="mt-4">Speaker Bio</h4>

  <p>
    Fan Shi is an Assistant Professor at the National University of Singapore, where he holds the prestigious NUS Presidential Young Professorship. His research lies at the intersection of artificial intelligence and robotics, with a focus on physical simulation, robot learning, and the development of scalable methods for embodied intelligence. His work has been recognized through awards and support from leading organizations, including the NVIDIA Academic Grant Program, Google Research, and the Swiss AI Initiative.
  </p>


  <!-- Abstract -->
  <h4 class="mt-4">Abstract</h4>

  <p>
    Robot learning fundamentally depends on access to abundant, high-quality, and low-cost data. Humanoid robots present unique challenges and opportunities—combining locomotion over rigid terrains (mostly) with manipulation of diverse, often deformable, objects. While synthetic data has driven remarkable progress in locomotion through deep reinforcement learning, manipulation remains limited by data scarcity and simulation fidelity. In this talk, I will discuss our recent advances in simulation technology inspired by our breakthroughs in computer graphics, aimed at enabling more effective humanoid learning for complex loco-manipulation tasks. Our new simulation engine delivers significant improvements in both speed and accuracy for deformable object dynamics, unlocking a wide range of contact-rich tasks previously deemed infeasible. I will conclude by outlining how these advances may shape the next frontier of humanoid intelligence, where realistic synthetic data bridges the gap between simulation and the real world.
  </p>

  <p class="text-right mt-4">
    <a href="#schedule">↑ Back to seminar schedule</a>
  </p>

  <!-- Scrolling Image Gallery -->
  <div class="seminar-gallery-wrapper">
    <div class="seminar-gallery-scroll" tabindex="0" aria-label="Fan image gallery. Scroll horizontally to view more images.">
      {% for i in (1..1) %}
        {% capture image_path %}assets/img/course/seminar2026/shifan/0{{ i }}.jpg{% endcapture %}

        <div class="seminar-gallery-slide">
          {% include figure.liquid
            loading="lazy"
            path=image_path
            class="rounded z-depth-1"
          %}
        </div>
      {% endfor %}
    </div>
  </div>

</section>


<!-- =========================================================
     TALK 2
     ========================================================= -->

<hr class="my-5">

<section id="victor" class="seminar-talk">

  <h2>
    My journey from architectural design to digital fabrication to construction robotics and beyond.
  </h2>

  <div class="row align-items-start mt-4">

    <div class="col-md-3 mb-4">
      {% include figure.liquid
        loading="eager"
        path="assets/img/course/seminar2026/victor/victor2.png"
        title="Professor LEUNG, Pok Yin Victor"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

    <div class="col-md-9">

      <h3>Prof. LEUNG, Pok Yin Victor</h3>

      <p class="text-muted">
        School of Creative Media<br>
        City University of Hong Kong
      </p>

      <p>
        <strong>Date:</strong> September 28, 2026<br>
        <strong>Time:</strong> 13:30–14:30<br>
        <strong>Location:</strong> Rm 4621
      </p>

    </div>

  </div>


  <h4 class="mt-4">Speaker Bio</h4>

  <p>
    Victor Leung is a researcher, educator, and maker working at the intersection of art, technology, and architecture. Victor’s practice focuses on robotic fabrication, computational design, and developing custom machines, tools, and end effectors for creative production. Victor is an Assistant Professor at the School of Creative Media, where he teaches courses on interactive machines, computational design, and digital fabrication.
  </p>

  <p>
  Central to his work is a belief that automation should serve to enhance human potential, not replace it. While much of his research focuses on advancing the precision and complexity of robotic fabrication, its broader aim is to address a persistent issue in society: the burden of repetitive, physically taxing labour. Industries like construction and manufacturing are still marked by tedious, manual work that limits human potential. By enabling machines to take on these repetitive roles, human intelligence can focus on higher-level, creative, and problem-solving tasks. In this way, automation is not a threat but as an opportunity to reshape our relationship with work and, ultimately, to design better environments for ourselves.
  </p>

  <p>
  Victor holds a Doctor of Science from ETH Zurich, where he developed new methods for robotic timber assembly using distributed robotic tools. His research explored how the design-to-assembly process can be transformed through robotics, addressing challenges like high assembly forces, precise alignment, and the simultaneous closure of integral timber joints. This work contributed to broader conversations on non-repetitive robotic assembly and earned recognition, including the Best Paper Award at CAADRIA 2021. Victor also completed a Master of Science in Architectural Studies (Design and Computation) at MIT and a Bachelor of Arts in Architectural Studies at the University of Hong Kong. His experience spans technical consulting for digital artists and architects, contributing to kinetic installations, custom robotic machines, and 3D-printed structures exhibited at venues such as the Venice Biennale and Science Gallery Melbourne. He has taught digital fabrication, computational design, and robotic assembly at institutions including ETH Zurich, MIT, the University of Hong Kong, the Singapore University of Technology and Design, and workshops at international venues such as the AA Visiting School and the ACADIA conference. He believes in hands-on, curiosity-driven learning, encouraging students to engage with the tools and technologies that shape our built environment.
  </p>

  <h4 class="mt-4">Abstract</h4>

  <p>
    The talk is a sharing session of my academic journey from HKU to MIT to ETH and how one project leads to another. Reflecting on my recent exhibition of showing a molten-sugar 3D printer that continued from a prototype I made more than 10 years ago. 
  </p>

  <!-- Scrolling Image Gallery -->
  <div class="seminar-gallery-wrapper">

    <div class="seminar-gallery-hint" aria-hidden="true">
      <span class="desktop-scroll-text">Scroll to view more</span>
      <span class="mobile-scroll-text">Swipe to view more</span>
      <span class="seminar-gallery-arrow">→</span>
    </div>
    <div class="seminar-gallery-scroll" tabindex="0" aria-label="Victor Leung image gallery. Scroll horizontally to view more images.">
      {% for i in (1..5) %}
        {% capture image_path %}assets/img/course/seminar2026/victor/0{{ i }}.jpg{% endcapture %}

        <div class="seminar-gallery-slide">
          {% include figure.liquid
            loading="lazy"
            path=image_path
            class="rounded z-depth-1"
          %}
        </div>
      {% endfor %}
    </div>
  </div>

  <p class="text-right mt-4">
    <a href="#schedule">↑ Back to seminar schedule</a>
  </p>

</section>

<!-- =========================================================
     END
     ========================================================= -->

<hr class="my-5">

<p class="text-center">
  <a href="#schedule">↑ Return to seminar schedule</a>
</p>