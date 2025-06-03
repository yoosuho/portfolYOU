---
title: "Development of a High-Efficiency, Low-Emission Multi-Channel Electric Drive PTO Power Module for Commercial Special-Purpose Vehicles"
layout: default
permalink: /pages/gr/
---
<h2>1. Research Overview</h2>
<p>
This project, led by <strong>Kwanglim Co., Ltd.</strong>, aimed to develop a <strong>multi-channel electric Power Take-Off (e-PTO)</strong> system applicable to commercial special-purpose vehicles such as dump trucks and cranes.
Traditional PTO systems mechanically link internal combustion engines to drive hydraulic equipment, leading to fuel consumption and emissions even when idling.
This project sought to eliminate those inefficiencies and environmental issues by adopting a high-voltage electric power system.
</p>
<p>
The e-PTO system integrates a high-power battery pack, inverter, power distribution unit (PDU), and vehicle control unit (VCU) into a single housing called the <strong>e-Powerpack</strong>.
<strong>VSPACE Co., Ltd.</strong> was responsible for the <strong>battery module and BMS development</strong>, covering mechanical design, thermal structure, BMS firmware, and communication interface.
</p>
<p>
The final output of this project was a mass-production-ready e-PTO system with three-channel output, achieving safety, durability, and energy efficiency benchmarks for electric special-purpose vehicles.
</p>

<h4>📌 Project Details</h4>
<ul>
  <li><strong>Project Title:</strong> Development of High-Efficiency, Low-Emission Multi-Channel Electric Power Take-Off System for Commercial Special-Purpose Vehicles</li>
  <li><strong>Program:</strong> Commercial Vehicle Innovation & Future Industry Ecosystem Program (Ministry of Trade, Industry and Energy, Korea)</li>
  <li><strong>Duration:</strong> April 2020 – December 2022</li>
  <li><strong>Lead Organization:</strong> Kwanglim Co., Ltd.</li>
  <li><strong>Participating Organizations:</strong>
    <ul>
      <li>VSPACE Co., Ltd. (Battery module design and BMS development)</li>
      <li>Global Engineering Co., Ltd. (Motor design and fabrication)</li>
      <li>KAI Tech (Power control unit testing and production evaluation)</li>
      <li>Korea Automotive Technology Institute (Cooling system analysis and optimization)</li>
      <li>Korea Electronics Technology Institute (Control software and functional safety verification)</li>
    </ul>
  </li>
  <li><strong>Project Director:</strong> Mr. Kim Ok-Geun (Kwanglim Co., Ltd.)</li>
  <li><strong>Battery System Lead:</strong> Mr. Suho Yu (Director, VSPACE Co., Ltd.)</li>
</ul>

<!-- Section 1 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/0.jpg" alt="Battery Assembly Photo 1" width="48%">
  <img src="/assets/gr/1.jpg" alt="Battery Assembly Photo 2" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/2.jpg" alt="Battery Assembly Photo 3" width="48%">
  <img src="/assets/gr/3.jpg" alt="Battery Assembly Photo 4" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/4.jpg" alt="Battery Mounting Model" width="48%">
  <img src="/assets/gr/5.jpg" alt="System Configuration Diagram" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/6.jpg" alt="e-PTO Image" width="48%">
  <img src="/assets/gr/7.jpg" alt="Battery Pack Installation" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/8.jpg" alt="Installed e-PTO on Vehicle" width="48%">
  <img src="/assets/gr/9.jpg" alt="Vehicle in Operation Photo 1" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/10.jpg" alt="Vehicle in Operation Photo 2" width="48%">
  <img src="/assets/gr/13.jpg" alt="Full Vehicle Model" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/16.jpg" alt="Battery Pack Engineering Drawing" width="48%">
</div>




<!-- 2. Research Motivation -->
<h2>2. Research Motivation</h2>
<p>
Conventional PTO systems operate by drawing mechanical power directly from the engine, resulting in constant fuel consumption and emissions even when the vehicle is stationary. In light of stricter emission regulations and rising fuel prices, a cleaner and more efficient power system became essential for the future of commercial special-purpose vehicles.
</p>
<p>
Additionally, growing demand for electrification in utility vehicles created an urgent need for a robust and modular electric PTO system. Unlike passenger EVs, these platforms require intermittent high-power output with thermal resilience and fault-tolerant architecture — challenges that are unique and not easily solved by off-the-shelf EV components.
</p>

<!-- Section 2 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/6.jpg" alt="e-PTO Module" width="48%">
  <img src="/assets/gr/8.jpg" alt="e-PTO Installed on Vehicle" width="48%">
</div>



<!-- 3. Technical Objectives -->
<h2>3. Technical Objectives</h2>
<ul>
  <li>Design and validate a modular <strong>123S1P battery pack</strong> using <strong>3.2 V 200 Ah prismatic LFP cells</strong></li>
  <li>Ensure compatibility with a <strong>three-channel e-PTO motor system</strong> capable of high transient current output</li>
  <li>Achieve <strong>thermal stability</strong> using a passive aluminum conduction path without active cooling mechanisms</li>
  <li>Implement a <strong>CAN-based BMS</strong> for real-time monitoring of voltage, temperature, and current</li>
  <li>Validate safety mechanisms including <strong>over-voltage, under-voltage, over-temperature, and short-circuit protection</strong></li>
  <li>Demonstrate <strong>mechanical vibration tolerance</strong> and on-vehicle electrical performance under working loads</li>
</ul>





<!-- 4. My Contributions -->
<h2>4. My Contributions</h2>
<p>
As the Battery System Lead at <strong>VSPACE Co., Ltd.</strong>, I oversaw the end-to-end development and integration of the high-voltage battery system for the e-PTO application.
My responsibilities covered both hardware and firmware domains, spanning component selection, 3D mechanical design, thermal safety architecture, and system-level validation.
</p>

<ul>
  <li>Selected and verified <strong>3.2 V 200 Ah prismatic LFP cells</strong> based on IR and capacity tests</li>
  <li>Designed the <strong>123S1P module architecture</strong> and aluminum enclosure to meet thermal and structural safety requirements</li>
  <li>Developed the <strong>BMS interface</strong> for CAN communication with inverter and vehicle controller (VCU)</li>
  <li>Led mechanical CAD modeling for vehicle integration, including mounting points and cooling interfaces</li>
  <li>Conducted final on-vehicle validation for vibration durability, thermal behavior, and electrical control handshake</li>
</ul>

<!-- Section 4 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/0.jpg" alt="Battery Assembly Photo" width="48%">
  <img src="/assets/gr/4.jpg" alt="Battery Mounting Model" width="48%">
</div>



<!-- 5. Engineering Approach -->
<h2>5. Engineering Approach</h2>
<p>
The design began with load estimation and thermal analysis of the PTO system under real operation cycles. To minimize thermal runaway risk and eliminate the need for active cooling, we implemented an <strong>aluminum frame structure</strong> that conducted heat away from the core.
</p>
<p>
The battery housing was constructed to <strong>IP67 standards</strong>, with foam supports and cell holders absorbing vibration from the chassis. We used rubber-padded aluminum endplates and laser-welded busbars to ensure high current reliability.
</p>
<p>
CAD modeling ensured compatibility with vehicle mounting points and clearance for electrical harnesses. The final battery pack design was simulated and validated through structural FEA and thermal CFD models before fabrication.
</p>

<!-- Section 5 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/5.jpg" alt="System Configuration Diagram" width="48%">
  <img src="/assets/gr/16.jpg" alt="Battery Pack Engineering Drawing" width="48%">
</div>




<!-- 6. Validation and Testing – Extended Dataset -->
<h2>6. Validation and Testing – Extended Dataset</h2>
<p>
The 123S1P battery pack underwent a full series of tests to verify its performance under real-world conditions. First, <strong>pre-assembly cell screening</strong> was conducted for internal resistance and capacity deviation. Only matched cells were accepted into final module assembly.
</p>
<p>
After mechanical assembly, the pack was instrumented with <strong>temperature sensors and current shunts</strong> for lab testing. Tests included <strong>high-current discharge cycles</strong>, <strong>thermal rise monitoring</strong>, <strong>vibration endurance</strong>, and <strong>insulation resistance checks</strong>.
</p>
<p>
Finally, the battery pack was mounted on the test vehicle and connected to the e-PTO system. Field validation included <strong>thermal soak runs</strong>, <strong>load cycling under working hydraulics</strong>, and <strong>CAN communication monitoring</strong> between the BMS and inverter.
</p>

<!-- Section 6 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/7.jpg" alt="Battery Pack Mounted in Vehicle" width="48%">
  <img src="/assets/gr/9.jpg" alt="Field Test Photo 1" width="48%">
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 10px;">
  <img src="/assets/gr/10.jpg" alt="Field Test Photo 2" width="48%">
</div>



<!-- 7. Research Outcomes -->
<h2>7. Research Outcomes</h2>
<p>
The developed e-PTO battery system met all target requirements for power output, durability, and vehicle-level integration. The 123S1P pack architecture proved stable across repeated high-current cycles, with minimal temperature rise and no cell imbalance over time.
</p>
<p>
The BMS communicated seamlessly with the inverter and vehicle controller, and all CAN nodes responded within latency specifications. The mechanical enclosure survived >10 hours of vibration testing and real-road operation without structural or thermal failure.
</p>
<p>
All modules were designed for <strong>mass production readiness</strong>, with manufacturable busbar layouts, laser-welded connections, and water/dust ingress protection.
</p>

<!-- Section 7 Image -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/13.jpg" alt="Complete Vehicle System Model" width="48%">
</div>



<!-- 8. Applied Product -->
<h2>8. Applied Product</h2>
<p>
The battery system developed through this research has been fully integrated into an electric Power Take-Off (e-PTO) system for commercial special-purpose vehicles.
It powers hydraulic cranes, tippers, and auxiliary devices without idling the engine, drastically improving fuel economy and reducing emissions.
</p>
<p>
Two configurations were tested: one for <strong>driving-only e-PTO</strong> and another for <strong>driving + generation (H-PTO)</strong>. The system has been successfully operated in real vehicles with active hydraulic loads.
</p>
<p>
The design allows for modular adaptation across various truck platforms with different voltage, capacity, and mounting configurations. This e-PTO system marks a practical transition step toward fully electrified utility fleets.
</p>

<!-- Section 8 Images -->
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="/assets/gr/14.jpg" alt="H-PTO Circuit Diagram" width="48%">
  <img src="/assets/gr/15.jpg" alt="E-PTO Circuit Diagram" width="48%">
</div>







<hr>
<p><a href="{{ site.baseurl }}/projects/">← Back to Projects</a></p>
