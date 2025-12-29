---
permalink: /
title: "About Me"
excerpt: "Robotics Engineer | Cornell MEng | Dyson R&D Alum"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Professional Styling Override */
  .archive__item-excerpt { font-size: 0.95em; }
  
  /* Project Grid Layout */
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }

  /* Project Cards */
  .project-card {
    border: 1px solid #e1e4e8;
    background-color: #ffffff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    border-color: #004d99; /* Deep Navy Accent */
  }

  .project-card h3 {
    margin-top: 0;
    color: #004d99;
    font-size: 1.1em;
  }

  .project-card p {
    font-size: 0.9em;
    color: #444;
    line-height: 1.5;
  }

  .project-link {
    display: inline-block;
    margin-top: 10px;
    color: #004d99;
    font-weight: bold;
    text-decoration: none;
    font-size: 0.9em;
  }
  
  .project-link:hover {
    text-decoration: underline;
  }
</style>

Hello, I am **Jorge Corpa Chung**. [cite_start]I am a Robotics Engineer currently pursuing a Master of Engineering at **Cornell University** (GPA 3.7)[cite: 4, 5], specializing in robotics and autonomous systems.

My work bridges the gap between mechanical design, embedded control, and AI. [cite_start]With a trilingual background (English, Spanish, Chinese)  [cite_start]and experience at **Dyson** and **NappLab**, I specialize in building full-stack robotic systems—from designing PCBs and optimizing FOV in CAD to migrating navigation stacks from ROS1 to ROS2[cite: 12, 19].

---

## Featured Projects

<div class="project-grid">

  <div class="project-card">
    <h3>Sisyphus Sand Table</h3>
    <p><strong>Role:</strong> System Integrator & Firmware Dev</p>
    <p>Integrated end-to-end system from CAD to RP2040 firmware. Developed dual stepper axis control for coordinated motion. [cite_start]<em>Featured on Raspberry Pi News and Hackaday.</em> [cite: 33, 35, 36]</p>
    <a href="/portfolio/sisyphus" class="project-link">View Project &rarr;</a>
  </div>

  <div class="project-card">
    <h3>Multi-Construction Robot</h3>
    <p><strong>Role:</strong> Mechanical & Systems Lead</p>
    <p>Designed a modular 3D-printed chassis with suspension and a novel wrist joint. Validated in Gazebo. [cite_start]<strong>Awarded Best MEng ECE Poster 2024.</strong> [cite: 22, 24, 26]</p>
    <a href="/portfolio/construction-robot" class="project-link">View Project &rarr;</a>
  </div>

  <div class="project-card">
    <h3>Leo Rover Design</h3>
    <p><strong>Role:</strong> Team Lead</p>
    [cite_start]<p>Led a team of 4 to integrate a multi-sensor suite (LiDAR, Depth Camera) and optimize ROS2 architecture on a Raspberry Pi for real-time navigation. [cite: 39, 40, 41]</p>
    <a href="/portfolio/leo-rover" class="project-link">View Project &rarr;</a>
  </div>

</div>

---

## Work Experience

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 25px;">
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">Research Assistant @ NappLab (Cornell)</h3>
    <em style="color: #666; font-size: 0.9em;">Aug 2024 - Present</em>
    <ul style="font-size: 0.95em; margin-top: 5px;">
       [cite_start]<li><strong>ROS Migration:</strong> Led the full-stack migration from ROS1 to ROS2, configuring Nav2 for autonomous navigation[cite: 19].</li>
       [cite_start]<li><strong>Hardware Optimization:</strong> Redesigned camera mounts via CAD to optimize FOV for 1x1 sq. ft. sampling.</li>
       [cite_start]<li><strong>Validation:</strong> Developed C++/Python scripts to automate sensor data capture for research validation[cite: 21].</li>
    </ul>
  </div>
</div>

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 25px;">
  <img src="/images/dyson.png" alt="Dyson Logo" style="width: 80px; height: auto; border-radius: 4px;">
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">R&D Hardware Intern @ Dyson</h3>
    <em style="color: #666; font-size: 0.9em;">June - Sept 2022</em>
    <ul style="font-size: 0.95em; margin-top: 5px;">
       [cite_start]<li>Designed hardware circuits and implemented closed-loop control algorithms on STM32 to maintain 0.01 precision.</li>
       [cite_start]<li>Created component emulators and co-developed a GUI for product testing[cite: 28, 30].</li>
       [cite_start]<li>Presented final results to senior management including the Head of Hardware[cite: 31].</li>
    </ul>
  </div>
</div>

## Education

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 15px;">
  <img src="/images/cornell_logo.png" alt="Cornell Logo" style="width: 60px; height: auto; border-radius: 4px;"> 
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">Cornell University</h3>
    <p style="margin: 5px 0; font-size: 0.95em;">
    <strong>MEng Electrical & Computer Engineering</strong> (Robotics Focus)<br>
    [cite_start]<em>GPA: 3.7</em> [cite: 5]
    </p>
  </div>
</div>

<div style="display: flex; gap: 20px; align-items: flex-start;">
  <img src="/images/uom.jpeg" alt="Manchester Logo" style="width: 60px; height: auto; border-radius: 4px;">
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">University of Manchester</h3>
    <p style="margin: 5px 0; font-size: 0.95em;">
    [cite_start]<strong>MSc Robotics</strong> (GPA: 3.80, 2024) [cite: 7]<br>
    [cite_start]<strong>BEng Electrical & Electronic Engineering</strong> (GPA: 3.67, 2023) [cite: 9]
    </p>
  </div>
</div>

<br>

## Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **Software** | [cite_start]Python, C/C++, MATLAB, OpenCV, Pytorch, Pandas, Numpy [cite: 12] |
| **Robotics** | [cite_start]ROS2 (Nav2), ROS1, Gazebo, SLAM, Kinematics, Behavior Trees [cite: 12, 19] |
| **Hardware** | [cite_start]STM32 (HAL), Altium, PCB Design, SolidWorks, Fusion 360 [cite: 12] |
| **Languages** | [cite_start]English (Fluent), Spanish (Native), Chinese (Native)  |

## Contact

* [cite_start]**Email:** [jorgecorpachung@yahoo.com](mailto:jorgecorpachung@yahoo.com) [cite: 3]
* **LinkedIn:** [linkedin.com/in/jorge-corpa-chung](https://www.linkedin.com/in/jorge-corpa-chung-278154195)
