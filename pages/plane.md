---
title: "Korea's First Manned All-Electric GA Aircraft Flight – Full Technical Research"
layout: default
permalink: /pages/plane/
---


<h1>Korea's First Manned All-Electric GA Aircraft Flight – Full Technical Research</h1>

<h2>1. Research Overview</h2>
<p>
This research marked a historic achievement: Korea's first successful flight of a manned, general aviation (GA)-class aircraft powered entirely by an in-house developed high-voltage battery system. The project encompassed the complete system development lifecycle—from cell characterization and thermal simulation to integration, environmental qualification, and real-world flight demonstration—serving as a foundational reference for Korea’s future airworthiness certification framework for electric propulsion.
  
- **Duration:** Apr 2020 – Dec 2023  
- **Funding:** Approx. 2.1M USD  
- **Lead Organization:** Korea Aerospace Research Institute (KARI) 
- **Participating Organizations:** AMOTECT, JNS, KETI, Vessel Aerospace, KATRA, Hanwha Aerospace, VSPACE
  
---

<h2>2. Research Motivation</h2>
<p>
The global push for carbon-neutral aviation has prompted major initiatives around electric propulsion. While global leaders like Pipistrel and Bye Aerospace demonstrated early success with electric training aircraft, Korea lacked a complete demonstration platform capable of supporting both regulatory development and real-world flight performance validation. This research aimed to close that gap with a domestically built, certifiable electric GA platform.
</p>

<h2>3. Technical Objectives</h2>
<ul>
  <li>Develop a 25.8 kWh high-voltage battery system based on cylindrical Li-ion cells with full aviation-grade safety features.</li>
  <li>Implement dual-module architecture optimized for CG balancing and thermal dissipation.</li>
  <li>Design and fabricate a robust enclosure compliant with vibration, drop, ingress, and pressure standards.</li>
  <li>Establish fault-tolerant CAN-based BMS telemetry integrated with propulsion and flight control systems.</li>
  <li>Validate system performance under iron-bird bench testing, environmental qualification, and manned flight.</li>
</ul>

<h2>4. My Contributions</h2>
<ul>
  <li>Defined pack architecture based on mission and CG constraints.</li>
  <li>Selected and qualified all 1,404 cylindrical cells.</li>
  <li>Designed enclosure and mechanical mounts validated by FEA.</li>
  <li>Developed STM32-based BMS hardware and bare-metal firmware.</li>
  <li>Conducted environmental testing, iron-bird integration, and final installation.</li>
  <li>Coordinated with propulsion teams and national research institutions (KARI, KETI) to align electrical and thermal specs across systems.</li>
</ul>

<h2>5. Engineering Approach</h2>

<h3>5.1 Cell Characterization and Pre-Selection</h3>
<p>Each of the 1,500+ cells was tested for capacity, internal resistance, and thermal behavior. Statistical filtering ensured a variance margin within ±2.1% in capacity and <5 mΩ in DCIR. Thermal tests ensured no hotspots under 3C load.</p>

<h3>5.2 System Architecture and Modeling</h3>
<p>Battery configuration was set as 156S9P (577 V, 25.8 kWh) split into front (156S6P) and rear (156S3P) packs. Thermal and structural performance was validated through CFD and FEA simulations. EMI and mechanical robustness were also considered.</p>

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-between;">
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/17.jpg" alt="Front battery CAD model" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 1. Front battery CAD model</p>
  </div>
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/14.jpg" alt="Propulsion system model" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 2. Propulsion system 3D model</p>
  </div>
</div>

<h3>5.3 Pack Fabrication and Mechanical Integration</h3>
<p>Each module was housed in an IP67-rated aluminum case with shock isolation. Copper busbars, thermistors, HVIL, and mounting rails were fabricated in-house. Sealing used EPDM gaskets and RTV.</p>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/1.jpg" alt="Battery pack 1" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 3. Fabricated battery module</p>
  </div>
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/2.jpg" alt="Battery pack 2" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 4. Side profile of battery enclosure</p>
  </div>
</div>

<h3>5.4 Embedded BMS Development</h3>
<p>STM32based BMS used passive balancing, redundant contactor logic, EEPROM logging, and custom CAN protocol. All code was bare-metal C, using interrupts and timers—no RTOS was used.</p>

<h3>5.5 Iron-Bird Testing</h3>
<p>The propulsion loop (battery-inverter-motor) was tested on the bench with throttle sweeps, regenerative braking, and fault injection scenarios.</p>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/5.jpg" alt="Iron-bird 1" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 5. Iron-bird test setup</p>
  </div>
  <div style="flex: 0 0 calc(50% - 10px); text-align: center;">
    <img src="/assets/plane/6.jpg" alt="Iron-bird 2" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 6. Bench test with full loop</p>
  </div>
</div>

<h3>5.6 Environmental Qualification</h3>
<p>DO-311-inspired tests were conducted: vibration (up to 8 g), thermal cycling (-10 °C to +50 °C), IP67 submersion, 1 m drop, and altitude simulation at 500 ft.</p>
<div style="text-align: center;">
  <img src="/assets/plane/18.jpg" alt="Battery discharge" style="width: 100%; max-height: 400px; object-fit: cover;">
  <p>Figure 7. Battery discharge thermal test</p>
</div>

<h3>5.7 Airframe Integration and Taxi Test</h3>
<p>Wiring, CAN routing, fuses, and kill switches were integrated with the KLA-100X airframe. Ground tests included throttle response, live telemetry, and emergency shutdown.</p>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/7.jpg" alt="Battery install" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 8. Battery module install</p>
  </div>
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/8.jpg" alt="Wiring inspection" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 9. Battery wiring check</p>
  </div>
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/9.jpg" alt="Pre-taxi" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 10. Ground inspection</p>
  </div>
</div>

<h3>5.8 Manned Flight Test</h3>
<p>The aircraft successfully performed Korea’s first electric-powered manned flight. BMS balancing remained within 15 mV. Cruise load was ~32 kW. Max discharge was 230 A.</p>
<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/10.jpg" alt="Pre-flight" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 11. Final check before flight</p>
  </div>
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/11.jpg" alt="In-flight" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 12. Actual flight</p>
  </div>
  <div style="flex: 0 0 calc(33.33% - 10px); text-align: center;">
    <img src="/assets/plane/12.jpg" alt="Team photo" style="width: 100%; max-height: 300px; object-fit: cover;">
    <p>Figure 13. Commemorative photo</p>
  </div>
</div>


<h2>6. Applied Product</h2>
<p>
This battery system was installed in the KLA-100X platform...
</p>

<h3>7. Flight Logs</h3>
<ul>
  <li><a href="https://www.cloudahoy.com/debrief/?key=29696pUw0kJbQkSo">Flight Log 1 – CloudAhoy Tracking</a></li>
  <li><a href="https://www.cloudahoy.com/debrief/?key=3vBD3WE9xm5K9fXfurc8">Flight Log 2 – Alternate Route Capture</a></li>
</ul>

<h3>8. Journal Publication</h3>
<p>
<strong>Modification and Development of Manned Electric Propulsion Lightweight Airplane</strong><br>
Journal of Aerospace System Engineering, 2023, Vol. 13(1)<br>
<a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11448316">View Full Paper</a>
</p>


<p><a href="{{ site.baseurl }}/blog/">← Back to Research</a></p>
