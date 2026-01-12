---
permalink: /
title: "Mohsen Amiri"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<table style="width:100%; border:none; border-collapse:collapse;">
  <tr>
    <td style="width:55%; vertical-align:top; border:none; padding-right:20px;">
      I'm a PhD candidate in Mechanical Engineering at <a href="https://www.wsu.edu">Washington State University</a> and part of the <a href="https://labs.wsu.edu/siaslab/">SIAS Lab</a>, advised by <a href="https://mme.wsu.edu/mme-personnel/wsu-profile/mehdi.hosseinzadeh/">Dr. Mehdi Hosseinzadeh</a>. 
      <br><br>
      My academic journey focuses on developing control theories, implementing them on real robots, and exploring robot interactions with humans. I am particularly interested in leveraging tools from **applied analysis** and **partial differential equations** to address challenges in real-world autonomy, and validating these methods on hardware across various robotic platforms (e.g., mobile robots, quadrupeds, and drones). Recently, I have also been working on **human-robot interaction** challenges, focusing on the safety and efficiency of both the robot and the interaction itself.
    </td>
    <td style="width:45%; vertical-align:top; border:none; text-align:center;">
      <img src="images/Hierarchical_Control_Structure.png" alt="Hierarchical Control Structure" style="width:100%; border-radius:10px;">
      <p style="font-size:0.8em; color:grey; margin-top:10px;"><i>Hierarchical Control Structure</i></p>
    </td>
  </tr>
</table>

---

## Research:

<table style="width:100%; border:none; border-collapse:collapse;">
  <tr>
    <td style="width:55%; vertical-align:top; border:none; padding-right:20px;">
      <h3>A dynamic embedding method for the real-time solution of time-varying constrained convex optimization problems</h3>
      <br>
      <b>M. Amiri</b>, I. Kolmanovsky, M. Hosseinzadeh
      <br>
      <i>Systems & Control Letters</i>, 2026
      <br>
      <a href="https://doi.org/10.1016/j.sysconle.2026.106352">[pdf]</a> / <a href="https://youtu.be/qGsw7iaElCI">[video]</a>
      <br><br>
      The proposed approach presents a method for solving time-varying constrained convex optimization problems in real time. The key idea is to embed the optimal solution within the internal state of a virtual dynamical system that evolves in parallel with the underlying optimization problem. 
      <br><br>
      This system tracks the optimal solution with a tunable bound and remains feasible at all times, even without prior knowledge of function dynamics.
    </td>
    <td style="width:45%; vertical-align:top; border:none; text-align:center;">
      <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius:10px;">
        <iframe src="https://www.youtube.com/embed/qGsw7iaElCI?si=MZl8qskdTns5xEGn" 
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
                frameborder="0" allowfullscreen></iframe>
      </div>
      <p style="font-size:0.8em; color:grey; margin-top:10px;"><i>Project Demonstration</i></p>
    </td>
  </tr>
</table>

---

<table style="width:100%; border:none; border-collapse:collapse;">
  <tr>
    <td style="width:55%; vertical-align:top; border:none; padding-right:20px;">
      <h3>CERTIS: A Computationally Efficient Model Predictive Control Framework for Resource-Constrained Safety-Critical Systems</h3>
      <br>
      <b>M. Amiri</b>, I. Kolmanovsky, M. Hosseinzadeh
      <br>
      <i>IEEE Transactions on Automatic Control (Under review)</i>, 2026
      <br>
      </a> / <a href="https://www.youtube.com/embed/sPeUhQ82Mpc?si=YlXA4fD86Owv7tMb">[video]</a>
      <br><br>
      Model Predictive Control (MPC) relies on online optimization that introduces implementation challenges, particularly for systems with limited computing resources or fast dynamics—thereby limiting MPC's applicability in many real-world scenarios. This method addresses these limitations by proposing a Computationally Efficient model pRedicTIve control Strategy (CERTIS).
      <br><br>
       A key feature of CERTIS is its ability to generate feasible and sub-optimal solutions even when the available computation time is insufficient to fully solve the MPC-related optimization problem. 
    </td>
    <td style="width:45%; vertical-align:top; border:none; text-align:center;">
      <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; border-radius:10px;">
        <iframe src="https://www.youtube.com/embed/sPeUhQ82Mpc?si=YlXA4fD86Owv7tMb"
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
                frameborder="0" allowfullscreen></iframe>
      </div>
      <p style="font-size:0.8em; color:grey; margin-top:10px;"><i>Project Demonstration</i></p>
    </td>
  </tr>
</table>
