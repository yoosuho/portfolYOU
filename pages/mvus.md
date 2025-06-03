---
title: "UAV-based Maritime Safety and Marine Ecosystem Management Battery System"
layout: default
permalink: /pages/mvus/
---

<h1>Hybrid Battery System Research for VTOL UAV</h1>

<h2>1. Research Overview</h2>
<p>This research was conducted as part of a national initiative led by the Korea Coast Guard and Vessel Aerospace. It focused on developing a scalable hybrid battery system suitable for VTOL UAVs performing long-endurance maritime missions such as illegal fishing surveillance and ecological monitoring. The system was required to deliver both high peak current for takeoff and endurance charging via onboard turbine generators during flight. The project lasted from November 2021 to December 2023 and involved multi-disciplinary collaboration across system design, control electronics, and validation engineering.</p>

- **Duration:** Apr 2021 – Dec 2023  
- **Funding:** Approx. 3.2M USD  
- **Lead Organization:** Vessel Aerospace 
- **Participating Organizations:** Korea Coast Guard, Seoyoung System, S&T, Seoul National University (and others) 
- **Client Organization:** Korea Coast Guard 
---



<h2>2. Research Motivation</h2>
<p>Typical electric UAV platforms are limited by their reliance on battery-only energy storage, which constrains flight range and duration. For long-range maritime surveillance operations—particularly those involving the Korean coastline and EEZ (Exclusive Economic Zone)—extended operation time is critical. This research was motivated by the need to combine the high instantaneous power of lithium-ion batteries with the long-duration capacity of gas turbine power generation, forming a redundant and mission-flexible energy system. The unique operational demand of this UAV required the battery to not only provide up to 18C discharge during takeoff, but also absorb energy inflow safely during cruise phases when turbine-generated charging is enabled</p>

<h2>3. Technical Objectives</h2>
<ul>
  <li>Design of a lightweight 14s modular battery system capable of both high-rate discharge and in-flight charging</li>
  <li>Implementation of advanced insulation methods for high-voltage protection in confined aircraft environments</li>
  <li>Development of STM32-based BMS firmware for real-time cell monitoring, fault detection, and turbine charge compatibility</li>
  <li>Architectural integration of the battery pack within a hybrid power system alongside a micro gas turbine unit</li>
</ul>

<h2>4. My Contributions</h2>
<ul>
  <li>Led battery system architecture, modeling, and implementation from concept to flight-ready product</li>
  <li>Performed exhaustive cell selection testing under thermal, load, and vibration conditions simulating UAV operation</li>
  <li>Developed custom BMS firmware using STM32 platform, including CAN/UAVCAN support for UAV integration</li>
  <li>Resolved high-voltage insulation failures caused by limited spacing within composite airframe compartments</li>
  <li>Proposed and implemented layout that separated battery pack from BMS while maintaining minimal latency and EMI protection</li>
</ul>

<div class="grid">
  <div>
    <img src="/assets/mvus/2.jpg" alt="Battery System View 1">
    <p><em>Figure 1. Completed 14s battery system with protective enclosure.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/3.jpg" alt="Battery System View 2">
    <p><em>Figure 2. Internal modular layout with EMI shielding.</em></p>
  </div>
</div>

<h2>5. Engineering Approach</h2>
<p>The power system architecture required significant adaptations due to the unusual mix of power input sources. We adopted a hybrid topology that allowed both the battery and the microturbine generator to share load responsibilities based on real-time power demand. To minimize resistance and manage EMI within this dynamic system, we designed short, thick copper busbars, carefully routed shielded signal lines, and fused protection mechanisms.
Thermal modeling was conducted to anticipate worst-case heat buildup inside the fuselage. The final design included phase-change thermal pads and aluminum casing with internal airflow routing for heat dispersion. Given that system voltage was locked at 14s for compatibility with avionics, high currents were inevitable; this required conservative cell spacing and additional dielectric layering.</p>


<div class="grid">
  <div>
    <img src="/assets/mvus/4.jpg" alt="Battery System View 3">
    <p><em>Figure 3. Output terminals and interconnect busbar layout.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/5.jpg" alt="Battery System View 4">
    <p><em>Figure 4. Assembled pack with structural supports and safety layers.</em></p>
  </div>
</div>

<div class="grid">
  <div>
    <img src="/assets/mvus/6.jpg" alt="Battery Install">
    <p><em>Figure 5. Pack installation into fuselage cavity.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/7.jpg" alt="Final Assembly">
    <p><em>Figure 6. Final assembly with completed harness routing.</em></p>
  </div>
</div>

<div class="grid">
  <div>
    <img src="/assets/mvus/8.jpg" alt="BMS Interface">
    <p><em>Figure 7. BMS interface showing sensor routing and logic lines.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/9.jpg" alt="UAV CAD Model">
    <p><em>Figure 8. UAV CAD model showing internal subsystem layout.</em></p>
  </div>
</div>

<h2>6. Validation and Testing – Extended Dataset</h2>
<p>System-level testing was performed on a custom-built Iron Bird platform that emulated the UAV’s electrical architecture. This included tests for over-discharge, sudden load spikes, turbine charging transitions, and full system restarts. Data was collected through CAN logging and high-frequency current probes.
Final validation involved tethered hover trials where the UAV operated with turbine charging enabled. Emergency fallback scenarios were induced by throttling down the turbine mid-flight to verify battery-only continuation.</p>


<div class="grid">
  <div>
    <img src="/assets/mvus/0.jpg" alt="Ironbird Test 1">
    <p><em>Figure 9. Iron Bird integration setup for real-time system simulation.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/1.jpg" alt="Ironbird Test 2">
    <p><em>Figure 10. Full system testbed with active BMS control interface.</em></p>
  </div>
</div>

<div class="grid">
  <div>
    <img src="/assets/mvus/10.jpg" alt="Tethered Test 1">
    <p><em>Figure 11. Pre-hover test with tether safety system.</em></p>
  </div>
  <div>
    <img src="/assets/mvus/11.jpg" alt="Tethered Test 2">
    <p><em>Figure 12. Hover test verifying flight continuity and fallback modes.</em></p>
  </div>
</div>

<h2>7. Research Outcomes</h2>
<ul>
  <li>Successfully validated hybrid power operation under full mission load scenarios</li>
  <li>Achieved in-flight battery charging with turbine-generated energy while maintaining UAV stability</li>
  <li>Resolved real-world EMI, vibration, and thermal constraints through iterative prototyping</li>
  <li>Established modular battery architecture applicable to scalable UAV platforms</li>
</ul>

<h2>8. Applied Product</h2>
<p>The developed system was flight-tested on an operational prototype and is now undergoing ruggedization for potential marine UAV deployment. Its success lays the foundation for future electric-turbine hybrid aerial systems, supporting long-duration patrols without reliance on ground-based battery swaps.</p>

</body>
</html>
<hr>


<p><a href="{{ site.baseurl }}/projects/">← Back to Projects</a></p>
