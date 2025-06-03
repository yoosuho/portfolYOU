---
title: "Development and demonstration of Onboard-Based Intelligent Avionics SW Platform Technology for Recognizing and Responding to Abnormal Situations of Urban Air Mobility"
layout: default
permalink: /pages/AI/
---

<h1>Development of an Intelligent Onboard Avionics Software Platform for Emergency Detection and Response in Urban Air Mobility (UAM)</h1>

<h2>1. Research Overview</h2>
<p>
This project aims to develop an intelligent, onboard avionics software platform for Urban Air Mobility (UAM) vehicles that can autonomously detect, assess, and respond to abnormal or emergency flight conditions. The system is being designed in compliance with the FACE (Future Airborne Capability Environment) standard, enabling high modularity, portability, and safety. Development is currently ongoing in its second year, with architectural design completed and progressive implementation underway.
</p>
<p><strong>Research Duration:</strong> April 2024 – December 2027<br>
<strong>Lead Organization:</strong> VSPACE<br>
<strong>Participating Organizations:</strong> DAVICH TRANS, Lihigh, Hanwha Systems, KETI, Korea National University of Transportation<br>
<strong>Role:</strong> Principal Development Organization</p>
<img src="/assets/AI/0.jpg" alt="System Concept Overview" style="width:100%; margin: 20px 0;"/>

<h2>2. Research Motivation</h2>
<p>
In the rapidly evolving UAM industry, operational safety is one of the most critical challenges, especially during abnormal conditions such as motor failures, sensor malfunctions, or communication loss. This research was initiated to develop an onboard system that can autonomously manage these emergency conditions in real time.
</p>

<h2>3. Technical Objectives</h2>
<ul>
  <li>Design a FACE-compliant avionics software architecture optimized for UAM platforms</li>
  <li>Implement real-time monitoring of flight-critical sensors and actuators</li>
  <li>Develop fault detection and classification algorithms for abnormal flight events</li>
  <li>Integrate emergency decision-making logic</li>
  <li>Validate the platform using SIL and HIL simulations</li>
  <li>Prepare the system for actual UAM aircraft integration</li>
</ul>
<img src="/assets/AI/1.jpg" alt="FACE Software Stack" style="width:100%; margin: 20px 0;"/>

<h2>4. My Contributions</h2>
<p>
As the Principal Investigator, I am currently leading the system-level design and technical direction of this national R&D project. My responsibilities include defining safety and functional requirements, overseeing the modular FACE-based architecture, managing subsystem integration, and coordinating industry and research partners to prepare for real vehicle testing.
</p>

<h2>5. Engineering Approach</h2>
<p>
We structured the system using FACE architecture layers, separating portable components, platform-specific services, and I/O interfaces. Emergency scenarios were defined, modeled as state-transition logic, and implemented using a real-time RTOS base. Testing procedures—including fault injection, mission rerouting, and autonomous landing—are being actively developed and evaluated.
</p>
<img src="/assets/AI/2.jpg" alt="FACE Container Architecture" style="width:100%; margin: 20px 0;"/>

<h2>6. Validation and Testing – Extended Dataset</h2>
<p>
Validation is currently being conducted using both software-in-the-loop (SIL) and hardware-in-the-loop (HIL) environments. Test scenarios include motor failure, battery faults, GPS spoofing, and communication loss. Real-time logs and telemetry are continuously analyzed to refine system response time and safety actions.
</p>
<img src="/assets/AI/3.jpg" alt="Optical Flow Test with Vision Processing" style="width:100%; margin: 20px 0;"/>

<h2>7. Research Outcomes</h2>
<ul>
  <li>FACE-compliant architecture and modular software stack under active development</li>
  <li>Progressive implementation of reusable detection-response software modules</li>
  <li>SIL and HIL performance verification in lab-scale testbeds</li>
  <li>Standardized interface definitions to support future system expansions</li>
</ul>
<img src="/assets/AI/4.jpg" alt="Sensor Fusion and Path Planning Architecture" style="width:100%; margin: 20px 0;"/>

<h2>8. Applied Product</h2>
<p>
The platform is currently being integrated into a single-seat multicopter UAM prototype. Preliminary testing is ongoing in tethered and laboratory environments. Full integration with autonomous control stacks is planned for year 3, followed by outdoor demonstration in national UAM test campaigns.
</p>
<img src="/assets/AI/5.jpg" alt="Sensor-Driven Execution Stack" style="width:100%; margin: 20px 0;"/>
<img src="/assets/AI/6.jpg" alt="UAM Autonomy Stack – Perception to Control" style="width:100%; margin: 20px 0;"/>

<hr>
<p><a href="{{ site.baseurl }}/projects/">← Back to Projects</a></p>
