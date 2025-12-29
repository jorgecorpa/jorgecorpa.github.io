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

Hello, I am **Jorge Corpa**. I am a Robotics Engineer currently pursuing a Master of Engineering at **Cornell University**. My work focuses on bridging the gap between mechanical design, embedded control, and AI-driven autonomy.

With a background in Electrical and Electronic Engineering (University of Manchester) and R&D experience at **Dyson**, I specialize in building full-stack robotic systems—from PCB design and STM32 firmware to ROS2 navigation and simulation.

---

## Featured Projects

<div class="project-grid">

  <div class="project-card">
    <h3>Multi-Construction Robot</h3>
    <p><strong>Role:</strong> Mechanical & Systems Lead</p>
    <p>Designed a replicable 3D-printed chassis with suspension and a novel wrist joint for a manipulator. Validated system kinematics in simulation.</p>
    <a href="/portfolio/construction-robot" class="project-link">View Project &rarr;</a>
  </div>

  <div class="project-card">
    <h3>Tethered Path Planning</h3>
    <p><strong>Role:</strong> Algorithm Developer</p>
    <p>Developed path planning algorithms for tethered robots to navigate complex environments without cable entanglement. Implemented in Python/ROS.</p>
    <a href="/portfolio/path-planning" class="project-link">View Project &rarr;</a>
  </div>

  <div class="project-card">
    <h3>Leo Rover Design</h3>
    <p><strong>Role:</strong> Robotics Engineer</p>
    <p>Led the integration of sensor arrays and navigation stack (ROS2) for the Leo Rover platform to achieve autonomous waypoint navigation.</p>
    <a href="/portfolio/leo-rover" class="project-link">View Project &rarr;</a>
  </div>

</div>

---

## Work Experience

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 25px;">
  <img src="/images/dyson.png" alt="Dyson Logo" style="width: 80px; height: auto; border-radius: 4px;">
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">R&D Hardware Intern @ Dyson</h3>
    <em style="color: #666; font-size: 0.9em;">Summer 2022</em>
    <ul style="font-size: 0.95em; margin-top: 5px;">
       <li>Engineered closed-loop control algorithms on STM32 microcontrollers, improving motor response.</li>
       <li>Designed PCBs and component emulators to accelerate hardware validation cycles.</li>
    </ul>
  </div>
</div>

## Education

<div style="display: flex; gap: 20px; align-items: flex-start;">
  <img src="/images/uom.jpeg" alt="Manchester Logo" style="width: 80px; height: auto; border-radius: 4px;">
  <div>
    <h3 style="margin: 0; font-size: 1.1em;">University of Manchester</h3>
    <p style="margin: 5px 0; font-size: 0.95em;">
    <strong>MSc Robotics</strong> (Distinction, 2024)<br>
    <strong>BEng Electrical & Electronic Engineering</strong> (2023)
    </p>
  </div>
</div>

<br>

## Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **Robotics** | ROS2, Gazebo, PX4, MoveIt, Navigation Stack |
| **Embedded** | STM32 (HAL), C/C++, PCB Design (Altium/KiCad), UART/I2C/SPI |
| **Software** | Python, MATLAB, Linux (Ubuntu), Git, Docker |
| **Languages** | English, Spanish, Chinese |
