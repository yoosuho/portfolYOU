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
<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="flex: 1;">
    <img src="/assets/AI/0.jpg" alt="System Concept Overview" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 1. Overall UAM emergency response framework, showing the linkage between the remote control system, onboard C-IMA software, and fault-aware landing scenarios.</p>
  </div>
  <div style="flex: 1;">
    <img src="/assets/AI/1.jpg" alt="FACE Software Stack" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 2. FACE-compliant architecture diagram, visualizing modular segmentation from OS to portable components, ensuring safety and reusability.</p>
  </div>
</div>

<h2>2. Research Motivation</h2>
<p>
In the rapidly evolving UAM industry, operational safety is one of the most critical challenges, especially during abnormal conditions such as motor failures, sensor malfunctions, or communication loss. While traditional aircraft rely on manual pilot responses or remote monitoring, UAM vehicles often require fully autonomous or semi-autonomous response capabilities. The motivation for this research stems from the need to embed real-time emergency detection and mitigation logic directly within the aircraft. This is essential not only for fail-operational capability but also for future airworthiness certification.
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

<h2>4. My Contributions</h2>
<p>
As the Principal Investigator, I am currently leading the system-level design and technical direction of this national R&D project. My responsibilities include defining safety and functional requirements, overseeing the modular FACE-based architecture, managing subsystem integration, and coordinating industry and research partners to prepare for real vehicle testing. I have also taken charge of modeling fault trees, designing fallback control strategies, and establishing the test pipeline through simulation and hardware bench configurations.
</p>

<h2>5. Engineering Approach</h2>
<p>
The system is engineered around the FACE (Future Airborne Capability Environment) architecture, which enables modular software development with defined communication and data exchange standards. The software stack is divided into segments: Portable Components (PCS), Platform-Specific Services (PSSS), Transport Services (TSS), I/O Services, and Operating System abstraction layers. Each emergency scenario—ranging from partial motor loss to full sensor blackout—is associated with state-transition logic and corresponding fallback actions.
</p>
<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="flex: 1;">
    <img src="/assets/AI/2.jpg" alt="FACE Container Architecture" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 3. FACE container-based architecture showing Dockerized deployment across redundant containers for modular fault isolation and recovery logic.</p>
  </div>
  <div style="flex: 1;">
    <img src="/assets/AI/3.jpg" alt="Optical Flow Test with Vision Processing" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 4. Vision-based fault recognition test using optical flow and keypoint tracking, used in our navigation fallback module under sensor failure.</p>
  </div>
</div>

<h2>6. Validation and Testing – Extended Dataset</h2>
<p>
Validation is being carried out using a combination of Software-in-the-Loop (SIL) and Hardware-in-the-Loop (HIL) setups. Emergency scenarios including GPS spoofing, battery over-discharge, rotor malfunction, and complete loss of communications are triggered through a custom-developed fault injection interface. The system’s response is measured by evaluating metrics such as reaction time, decision latency, and recovery trajectory success.
</p>
<p>
Real-time telemetry, system logs, and motor behavior are continuously recorded. Additionally, benchmark tests using inertial-only navigation and mission rerouting are used to verify fallback logic robustness. We also monitor system bus traffic, partition isolation performance, and watchdog mechanisms under prolonged operation.
</p>

<h2>7. Research Outcomes</h2>
<ul>
  <li>Development of a modular, FACE-standard compliant avionics software platform tailored to emergency response needs</li>
  <li>Construction of a complete SIL/HIL validation bench with repeatable emergency scenario injection</li>
  <li>Deployment of core detection modules into a multicopter hardware testbed under simulated rotor failure</li>
  <li>Published interface specifications for multi-partition architecture to ensure long-term scalability and certification readiness</li>
</ul>
<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="flex: 1;">
    <img src="/assets/AI/4.jpg" alt="Sensor Fusion and Path Planning Architecture" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 5. System-level perception and planning architecture used for context-aware emergency response decisions including trajectory replanning.</p>
  </div>
  <div style="flex: 1;">
    <img src="/assets/AI/5.jpg" alt="Sensor-Driven Execution Stack" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 6. Execution stack diagram for embedded decision engines, integrating V2X, radar, and inertial navigation sources for robust recovery logic.</p>
  </div>
</div>

<h2>8. Applied Product</h2>
<p>
The platform is currently undergoing integration with a custom-built UAM prototype based on a single-seat multicopter configuration. Laboratory testing is being conducted in a tethered flight setup with injected emergency cases. Real-world flight demonstrations are planned for the upcoming test campaign under the Korean UAM Grand Challenge framework.
</p>
<p>
Software modules are deployed in a redundant computing container environment. Each container includes navigation, sensor fusion, emergency handling, and interface modules. The system is also being evaluated for conformance to DO-178C and FACE validation suites. We anticipate that the platform will be capable of self-contained emergency response—including autonomous diversion and forced landing—in uncontrolled flight conditions.
</p>
<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="flex: 1;">
    <img src="/assets/AI/6.jpg" alt="UAM Autonomy Stack – Perception to Control" style="width:100%;"/>
    <p style="font-size: 0.9em;">Figure 7. Full autonomy stack integrating perception, planning, and control modules, aligned with our modular avionics interface structure.</p>
  </div>
</div>

<hr>
<p><a href="{{ site.baseurl }}/projects/">← Back to Projects</a></p>
