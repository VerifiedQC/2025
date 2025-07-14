---
layout: page
title: First Workshop on Verification of Quantum Computing (VQC 2025)
subtitle: A CAV 2025 Workshop
cover-img: "/assets/img/zagreb.png"
---

<div class="workshop-details">
    <span class="workshop-detail">
        <i class="fas fa-calendar-alt"></i> July 21, 2025
    </span>
    <span class="workshop-detail">
        <i class="fas fa-location-dot"></i> <p><a href="https://www.google.com/maps/place/Faculty+of+Electrical+Engineering+and+Computing/@45.8003692,15.968797,17z/data=!3m1!4b1!4m6!3m5!1s0x4765d6f150cf2ccd:0x739e5c279fd98531!8m2!3d45.8003692!4d15.9713773!16zL20vMGd3dDd3?entry=ttu&g_ep=EgoyMDI1MDMxNy4wIKXMDSoJLDEwMjExNDUzSAFQAw%3D%3D">Building D of the Faculty of Electrical Engineering and Computing, </a>  <br/> University of Zagreb, Zagreb, Croatia </p>
    </span>
</div>

<!-- [Presentation Submission](https://easychair.org/conferences/?conf=vqc2025) -->

<!-- <span style="color:red">Due to several requests, we have extended the submission deadline to May 15.</span> -->

<!-- <span style="color:red">The notification deadline is extended to June 15. If you need to receive the result earlier for travel arrangements, please feel free to contact the co-chairs.</span> -->

#### Organizers
- Runzhou Tao (University of Maryland)
- Yu-Fang Chen (Academia Sinica)

#### Invited Speakers
- Ross Duncan (Quantinuum)
- Aws Albarghouthi (University of Wisconsin-Madison)
- Mingsheng Ying (University of Technology Sydney)

#### Program
<table>
  <thead>
    <tr>
      <th style="width: 120px;">Time</th>
      <th>Event</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>8:30–9:00</td><td><strong>Breakfast</strong></td></tr>
    <tr><td>9:00–9:05</td><td><strong>Opening</strong></td></tr>
    <tr><td colspan="2"><em>Session 1</em></td></tr>
    <tr><td>9:05–9:50</td><td><details><summary><strong>Keynote: What Should We Verify?</strong> (show abstract)<br>Ross Duncan</summary>
Verification usually means to guarantee that a computational system is correct with respect to some specification. Can this definition survive in the context of quantum computing? What parts of the system can be verified? What notions of correctness are helpful? What properties of realistic systems can be verified? What* should *we verify? I will survey the field and give some perspective on the challenges and opportunities for automated verification of quantum software. Spoiler: it's the compiler.
</details> </td></tr>
    <tr><td>9:50–10:10</td><td><strong>Interval-based Analysis of Quantum Variational Computing</strong><br>Nicola Assolini, Luca Marzari, Isabella Mastroeni and Alessandra Di Pierro</td></tr>
    <tr><td>10:10–10:30</td><td><strong>Finding Photonics Circuits with SMT Solvers</strong><br>Marco Lewis and Benoît Valiron</td></tr>
    <tr><td>10:30–11:00</td><td><strong>Coffee break</strong></td></tr>
    <tr><td colspan="2"><em>Session 2</em></td></tr>
    <tr><td>11:00–11:45</td><td><details>
<summary><strong>Keynote: A Practical Quantum Hoare Logic with Classical Variables</strong> (show abstract)<br>Mingsheng Ying</td></summary>
We present a Hoare-style logic for reasoning about quantum programs with classical variables. Our approach offers several improvements over previous work:<br><br>
(1) Enhanced expressivity of the programming language: Our logic applies to quantum programs with classical variables that incorporate quantum arrays and parameterized quantum gates, which have not been addressed in previous research on quantum Hoare logic, either with or without classical variables.<br><br>
(2) Intuitive correctness specifications: In our logic, preconditions and postconditions for quantum programs with classical variables are specified as a pair consisting of a classical first-order logical formula and a quantum predicate formula (possibly parameterized by classical variables). These specifications offer greater clarity and align more closely with the programmer's intuitive understanding of quantum and classical interactions.<br><br>
(3) Simplified proof system: By introducing a novel idea in formulating a proof rule for reasoning about quantum measurements, along with (2), we develop a proof system for quantum programs that requires only minimal modifications to classical Hoare logic. Furthermore, this proof system can be effectively and conveniently combined with classical first-order logic to verify quantum programs with classical variables.<br><br>
As a result, the learning curve for quantum program verification techniques is significantly reduced for those already familiar with classical program verification techniques, and existing tools for verifying classical programs can be more easily adapted for quantum program verification.
</details></td></tr>
    <tr><td>11:45–12:05</td><td><strong>Hardware-Optimal Quantum Algorithms</strong><br>Stefanie Muroya, Krishnendu Chatterjee and Thomas Henzinger</td></tr>
    <tr><td>12:05–14:00</td><td><strong>Lunch</strong></td></tr>
    <tr><td colspan="2"><em>Session 3</em></td></tr>
    <tr><td>14:00–14:45</td><details>
<summary><strong>Keynote: Synthesizing Quantum Compilers</strong> (show abstract)<br>Aws Albarghouthi</summary>
The promise of quantum computing has tantalized researchers for decades, and recent breakthroughs in physical implementations have brought this technology closer to reality. However, the quantum computing landscape remains highly dynamic: competing physical substrates, fault tolerance schemes, and architectures continue to emerge with no clear frontrunner. This diversity creates a significant bottleneck in the compilation pipeline – developing and maintaining separate compilers for each new device or experimental setup is both time-consuming and error-prone.<br><br>

In this talk, I will present an alternative approach: automatically synthesizing device-specific quantum circuit compilers. This synthesis-based methodology enables rapid iteration while maintaining correctness guarantees. I will focus on the optimizer component, which reduces circuit size to minimize quantum computation errors. I will demonstrate how automatically synthesized optimizers can achieve superior performance compared to sophisticated hand-crafted alternatives. I will also discuss recent results on synthesizing device-specific mapping and routing algorithms.
</details></td></tr>
    <tr><td>14:45–15:05</td><td><strong>Certified Randomness from Quantum Supremacy</strong><br>Scott Aaronson and Shih-Han Hung</td></tr>
    <tr><td>15:05–15:30</td><td><strong>Poster Session</strong></td></tr>
    <tr><td>15:30–16:00</td><td><strong>Coffee break</strong></td></tr>
    <tr><td colspan="2"><em>Session 4</em></td></tr>
    <tr><td>16:00–16:20</td><td><strong>Analysing Quantum Programs using Automata</strong><br>Parosh Aziz Abdulla, Yo-Ga Chen, Yu-Fang Chen, Kai-Min Chung, Lukáš Holík, Ondrej Lengal, Jyun-Ao Lin, Fang-Yi Lo, Wei-Lun Tsai and Di-De Yen</td></tr>
    <tr><td>16:20–16:40</td><td><strong>On-Chip Verified Quantum Computation with an Ion-Trap Quantum Processing Unit</strong><br>Cica Gustiani, Dominik Leichte and Daniel Mills</td></tr>
    <tr><td>16:40–17:00</td><td><strong>Certifying Adversarial Robustness in Quantum Machine Learning: From Theory to Physical Validation</strong><br>Ji Guan</td></tr>
    <tr><td>17:00–17:30</td><td><strong>Panel Discussion</strong></td></tr>
  </tbody>
</table>

#### Keynote Abstracts

 


#### Posters
- **Barrier Certificates for Quantum Computing.** <br> Marco Lewis, Sadegh Soudjani and Paolo Zuliani
- **Compact and efficient formalism for resource and termination estimation in quantum programs.** <br>	Jad Issa, Christophe Chareton and Romain Péchoux
- **DisQ: A Model of Distributed Quantum Processors.** <br> Le Chang, Saitej Yavvari, Rance Cleaveland, Samik Basu and Liyi Li	
- **Hybrid Programming Language for Cryptography in Rocq.** <br> Zhenhao Li and Li Zhou

#### Program Committee
- Runzhou Tao (University of Maryland)
- Yu-Fang Chen (Academia Sinica)
- Alfons Laarman (Leiden University)
- Christophe Chareton (LORIA-CELLO)
- Ondrej Lengal (Brno University of Technology)
- Max Tschaikowski (Aalborg University)
- Nengkun Yu (Stony Brook University)
- Ji Liu (Argonne National Laboratory)
- Zichang He (JPMorgan Chase)
- Li Zhou (Max Planck Institute for Security and Privacy)
- Ferhat Erata (Yale University)



