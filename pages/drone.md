---
title: "Development of a 100 kg-class Heavy Cargo Drone with Single-Propeller Failure Tolerance"
layout: default
permalink: /pages/drone/
---
<h1>🚛 Development of a 100 kg-class Heavy Cargo Drone with Single-Propeller Failure Tolerance</h1>

<p><strong>Duration:</strong> January 2023 – December 2024<br>
<strong>Lead Organization:</strong> VSPACE<br>
<strong>Role:</strong> Project Lead for Full Aircraft Development</p>

<hr>

<h2>🔧 Project Overview</h2>
<p>
This project focuses on the development of a heavy-lift X8 multicopter drone with a maximum takeoff weight (MTOW) of 225 kg and a payload capacity of 100 kg. Unlike conventional multicopters, this platform is designed to tolerate single-propeller failure while maintaining controlled flight, enabling safe deployment in high-risk delivery and logistics environments.
</p>

<p>
The project includes mechanical design, frame reinforcement, structural validation, flight controller configuration for fault handling, and actual demonstration of stable flight with simulated failures.
</p>

<h2>🧠 My Contributions</h2>
<ul>
  <li>Designed and assembled the entire drone frame for high-load conditions</li>
  <li>Integrated high-voltage battery pack with custom STM32-based BMS and CAN communication</li>
  <li>Performed structural analysis (FEA) to verify integrity under propeller failure torque</li>
  <li>Configured fault-tolerant X8 motor layout with custom flight controller tuning</li>
  <li>Executed tethered and untethered flight tests with single-motor failure scenarios</li>
</ul>

<h2>📈 Outcomes</h2>
<ul>
  <li>Successfully demonstrated real flight with single-propeller fault tolerance</li>
  <li>Validated structural and power system resilience for 100 kg-class logistics missions</li>
  <li>Confirmed effectiveness of BMS, ESC synchronization, and vibration resistance</li>
</ul>

<h2>🖼️ Gallery</h2>
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem;">

  <!-- Modeling (0) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/0.jpg" alt="CAD Model" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">CAD model of the 100 kg-class heavy-lift cargo drone (X8 layout).</figcaption>
  </figure>

  <!-- Completed Aircraft (1–3) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/1.jpg" alt="Drone Front View" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Completed drone – front view showing twin boom structure and landing gear.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/2.jpg" alt="Drone Diagonal" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Three-quarter view showing propulsion modules and motor spacing.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/3.jpg" alt="Drone Side View" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Side view of final assembled drone ready for integration testing.</figcaption>
  </figure>

  <!-- Assembly + BMS (4–5) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/4.jpg" alt="Assembly Process" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Frame assembly and propulsion mount alignment in progress.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/5.jpg" alt="BMS and Battery" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Internally developed STM32-based BMS integrated into the powertrain.</figcaption>
  </figure>

  <!-- Structural Analysis (6–7) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/6.jpg" alt="FEA Results" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">FEA simulation of stress concentration under asymmetric thrust failure.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/7.jpg" alt="FEA Displacement" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Displacement and deflection analysis under peak torque loading.</figcaption>
  </figure>

  <!-- Safety Tether Test (8–9) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/8.jpg" alt="Tether Test" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Tethered hover test with one motor intentionally disabled.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/9.jpg" alt="Safety Verification" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Stability recovery and oscillation damping captured during fault simulation.</figcaption>
  </figure>

  <!-- Real Flight Test (10–11) -->
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/10.jpg" alt="Outdoor Flight" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Outdoor flight test in open area confirming fault-tolerant hover.</figcaption>
  </figure>
  <figure>
    <img src="{{ site.baseurl }}/assets/cargo-drone/11.jpg" alt="Midair Flight Test" style="width: 100%; height: 250px; object-fit: cover;">
    <figcaption style="font-size: 0.9em;">Midair flight capture validating system control under load imbalance.</figcaption>
  </figure>
</div>

<h2>🎥 YouTube Demo</h2>
<p>
This project was documented through a 4-part video series showing the full development and fault-tolerant flight validation process.
</p>
<ul>
  <li><a href="https://www.youtube.com/watch?v=MUU4dJ49hcs" target="_blank">▶ Part 1: Frame Design and Structural Assembly</a></li>
  <li><a href="https://www.youtube.com/watch?v=VaOsciePToo" target="_blank">▶ Part 2: Welding and Power System Integration</a></li>
  <li><a href="https://www.youtube.com/watch?v=qfeal6rIaIg" target="_blank">▶ Part 3: Final Assembly and Power-On Test</a></li>
  <li><a href="https://www.youtube.com/watch?v=6S9ZqQECzDM" target="_blank">▶ Part 4: Tethered and Free Flight Fault-Tolerance Demo</a></li>
</ul>

<hr>
<p><a href="{{ site.baseurl }}/projects/">← Back to Projects</a></p>
