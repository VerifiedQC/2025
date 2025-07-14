| Time         | Event |
|--------------|-------|
| 8:30–9:00    | **Breakfast** |
| 9:00–9:05    | **Opening** |
| _Session 1_    |       |
| 9:05–9:50    | **Keynote: What Should We Verify?**<br> Ross Duncan|
| 9:50–10:10   | **Interval-based Analysis of Quantum Variational Computing**<br>Nicola Assolini, Luca Marzari, Isabella Mastroeni and Alessandra Di Pierro |
| 10:10–10:30  | **Finding Photonics Circuits with SMT Solvers**<br>Marco Lewis and Benoît Valiron |
| 10:30–11:00  | **Coffee break** |
| _Session 2_    |       |
| 11:00–11:45  | **Keynote: A Practical Quantum Hoare Logic with Classical Variables.**<br>Mingsheng Ying |
| 11:45–12:05  | **Hardware-Optimal Quantum Algorithms**<br>Stefanie Muroya, Krishnendu Chatterjee and Thomas Henzinger |
| 12:05–14:00  | **Lunch** |
| _Session 3_    |       |
| 14:00–14:45  | **Keynote: Synthesizing Quantum Compilers**<br>Aws Albarghouthi |
| 14:45–15:05  | **Certified Randomness from Quantum Supremacy**<br>Scott Aaronson and Shih-Han Hung |
| 15:05–15:30  | **Poster Session** |
| 15:30–16:00  | **Coffee break** |
| _Session 4_    |       |
| 16:00–16:20  | **Analysing Quantum Programs using Automata**<br>Parosh Aziz Abdulla, Yo-Ga Chen, Yu-Fang Chen, Kai-Min Chung, Lukáš Holík, Ondrej Lengal, Jyun-Ao Lin, Fang-Yi Lo, Wei-Lun Tsai and Di-De Yen |
| 16:20–16:40  | **On-Chip Verified Quantum Computation with an Ion-Trap Quantum Processing Unit**<br>Cica Gustiani, Dominik Leichte and Daniel Mills |
| 16:40–17:00  | **Certifying Adversarial Robustness in Quantum Machine Learning: From Theory to Physical Validation**<br>Ji Guan |
| 17:00–17:30  | **Panel Discussion** |

<h3><strong>Abstract:</strong></h3>
<details>
<summary><em>What Should We Verify? Ross Duncan</em></summary>
Verification usually means to guarantee that a computational system is correct with respect to some specification. Can this definition survive in the context of quantum computing? What parts of the system can be verified? What notions of correctness are helpful? What properties of realistic systems can be verified? What* should *we verify? I will survey the field and give some perspective on the challenges and opportunities for automated verification of quantum software. Spoiler: it's the compiler.
</details> 
<details>
<summary><em>A Practical Quantum Hoare Logic with Classical Variables. Mingsheng Ying</em></summary>
We present a Hoare-style logic for reasoning about quantum programs with classical variables. Our approach offers several improvements over previous work:<br><br>
(1) Enhanced expressivity of the programming language: Our logic applies to quantum programs with classical variables that incorporate quantum arrays and parameterized quantum gates, which have not been addressed in previous research on quantum Hoare logic, either with or without classical variables.<br><br>
(2) Intuitive correctness specifications: In our logic, preconditions and postconditions for quantum programs with classical variables are specified as a pair consisting of a classical first-order logical formula and a quantum predicate formula (possibly parameterized by classical variables). These specifications offer greater clarity and align more closely with the programmer's intuitive understanding of quantum and classical interactions.<br><br>
(3) Simplified proof system: By introducing a novel idea in formulating a proof rule for reasoning about quantum measurements, along with (2), we develop a proof system for quantum programs that requires only minimal modifications to classical Hoare logic. Furthermore, this proof system can be effectively and conveniently combined with classical first-order logic to verify quantum programs with classical variables.<br><br>
As a result, the learning curve for quantum program verification techniques is significantly reduced for those already familiar with classical program verification techniques, and existing tools for verifying classical programs can be more easily adapted for quantum program verification.
</details> 
<details>
<summary><em>Synthesizing Quantum Compilers. Aws Albarghouthi</em></summary>
The promise of quantum computing has tantalized researchers for decades, and recent breakthroughs in physical implementations have brought this technology closer to reality. However, the quantum computing landscape remains highly dynamic: competing physical substrates, fault tolerance schemes, and architectures continue to emerge with no clear frontrunner. This diversity creates a significant bottleneck in the compilation pipeline – developing and maintaining separate compilers for each new device or experimental setup is both time-consuming and error-prone.<br><br>

In this talk, I will present an alternative approach: automatically synthesizing device-specific quantum circuit compilers. This synthesis-based methodology enables rapid iteration while maintaining correctness guarantees. I will focus on the optimizer component, which reduces circuit size to minimize quantum computation errors. I will demonstrate how automatically synthesized optimizers can achieve superior performance compared to sophisticated hand-crafted alternatives. I will also discuss recent results on synthesizing device-specific mapping and routing algorithms.
</details> 
