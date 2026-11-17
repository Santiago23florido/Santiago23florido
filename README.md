<div align="center">

<img src="https://capsule-render.vercel.app/api?type=blur&height=210&color=0:00D9FF,100:1F6FEB&text=Santiago%20Florido%20G%C3%B3mez&fontSize=48&fontColor=FFFFFF&stroke=1E3A8A&strokeWidth=2&animation=twinkling&fontAlignY=52" width="100%" alt="Santiago animated banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=760&lines=Robot+Learning+%26+Cross-Embodiment+Transfer;Neuromotor+Interfaces+%7C+HD-sEMG+Decoding;Reinforcement+Learning+in+Isaac+Lab+%26+MuJoCo;MSc+Cyber-Physical+Systems+%40+IP+Paris" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiago-florido-gómez-722193232/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Santiago23florido)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:santiago.florido@ensta-paris.fr)

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&section=header&color=0:7DD3FC,100:1E3A8A&text=Welcome%20to%20my%20GitHub!&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32" width="100%"/>

</div>

---

## 🎯 About Me

```python
class ResearchStudent:
    def __init__(self):
        self.name      = "Santiago Florido Gómez"
        self.role      = "MSc student — Cyber-Physical Systems, Institut Polytechnique de Paris"
        self.also      = "Engineering degree (AI track) — ENSTA Paris"
        self.background = "B.Sc. Mechatronics Engineering — Universidad EIA, Colombia"
        self.location  = "Palaiseau, Île-de-France, France"
        self.languages = ["Spanish (native)", "English (C1)", "French (B2)"]

    def research(self):
        return {
            "🤖 Robot learning":        "cross-embodiment skill transfer between humanoids (Isaac Lab)",
            "🧠 Neuromotor interfaces": "motor-unit decoding from HD-sEMG to drive a musculoskeletal hand",
            "🩺 Safe RL":               "endovascular catheter navigation posed as a constrained MDP",
            "📈 Efficient learning":    "certified functional descent for neural-architecture growth",
        }

    def whats_next(self):
        return {
            "Apr–Sep 2027": "Visiting research student — Neuromechanics & Rehabilitation "
                            "Technology Group, Imperial College London (Prof. Dario Farina)",
            "From late 2027": "Looking for a PhD in robot learning / neuromotor interfaces",
        }
```

<div align="center">

### 🌟 Core Competencies

<table>
<tr>
<td align="center" width="33%">
<img src="https://img.icons8.com/fluency/96/000000/robot-2.png" width="60"/><br/>
<b>Robot Learning & Simulation</b><br/>
Isaac Lab / Isaac Sim, MuJoCo<br/>
PPO (rsl_rl), Flow Matching<br/>
Cross-Embodiment Transfer
</td>
<td align="center" width="33%">
<img src="https://img.icons8.com/fluency/96/000000/electrical-sensor.png" width="60"/><br/>
<b>Neuromotor Interfaces</b><br/>
HD-sEMG Decomposition<br/>
Motor-Unit Decoding<br/>
MyoSuite / Musculoskeletal Models
</td>
<td align="center" width="33%">
<img src="https://img.icons8.com/fluency/96/000000/control-panel.png" width="60"/><br/>
<b>Control & Signals</b><br/>
System ID, Digital Control<br/>
PID / RST, CNN–LSTM Pipelines<br/>
Embedded Systems, ROS 2
</td>
</tr>
</table>

</div>

---

## 📄 Publications

| Year | Work | Venue |
|:---:|:---|:---|
| 2026 | **CAGE-NAS: Certified Functional Descent for Efficient Model Growth**<br/>*S. Florido Gómez, S. Rivaud* — [code](https://github.com/Santiago23florido/functional-gradient-growth) | **AXIOM workshop @ NeurIPS 2026** (accepted) |
| 2025 | **Low-order dynamic modeling and control of a neonatal incubator**<br/>*S. Florido Gómez, J. D. Gómez Bedoya, T. Manrique, R. A. Torres* — [code](https://github.com/Santiago23florido/Neonatal-Incubator-Dynamic-Model-and-Control) | [**IEEE CCAC 2025**](https://ieeexplore.ieee.org/document/11259151) |

---

## 🔬 Research Experience

**Visiting Research Student** — Neuromechanics & Rehabilitation Technology Group, *Imperial College London*  ·  **Apr–Sep 2027 (incoming)**
Prof. Dario Farina, with Matteo Pizzi. Decomposition of high-density surface EMG **during hand movement**: translating neuromuscular activity into reliable representations of motor intention under changing movement conditions.

**Research Intern (PRe)** — équipe TAU / LISN, *Inria Saclay — Université Paris-Saclay*  ·  **May–Aug 2026**
Neural-architecture growth for frugal learning. Certified functional descent: using functional-gradient information in the tangent space of the network to decide when a model should grow rather than keep training. Led to a first-author paper accepted at the AXIOM workshop, NeurIPS 2026.

**Data & Machine Learning Analyst** — *Celerix*, Medellín  ·  **Dec 2024 – Sep 2025**
Demand forecasting and pricing models, automated ETL pipelines, embedding-based NLP components.

---

## 🚀 Featured Projects

### 🦿 [Cross-Embodiment Humanoid Skill Transfer](https://github.com/Santiago23florido/lHumanoid-Soccer-Isaac-Lab) · Isaac Lab

A locomotion skill learned on a **Unitree G1** runs **zero-shot** on a **NAO** that never trained on it — nine times lighter and 2.3 times shorter. The skill crosses as a *contract* rather than as joint angles: the short future of a 27-number state describing what the body does, made dimensionless with its own leg length, mass and gravity. Each skill's generator is trained once by flow matching on the source robot; each body's estimator and tracker are trained once and never see a transferred skill — so **N skills on M bodies cost N + M trainings instead of N × M**.

> **192 / 192 episodes without a fall** per body and skill, at 1.00–1.14× the teacher's speed. On the NAO, the zero-shot tracker stays closer to the teacher's gait than a tracker trained on the skill itself.
> *All results are in simulation (Isaac Lab). One source body and one target body — not arbitrary morphologies.*

`Isaac Lab` `Isaac Sim` `PyTorch` `PPO (rsl_rl)` `Flow Matching` `Dimensional Analysis`

---

### 🖐️ [Musculoskeletal Hand Control from Motor Units](https://github.com/Santiago23florido/Musculoskeletal-Hand-Simulation) · MuJoCo / MyoSuite

Decoding **individual motor units** from high-density surface EMG while the joint moves fast, to drive a simulated musculoskeletal hand (MyoSuite's MyoHand). The open problem: decomposition methods lose track of motor units exactly when the limb moves quickly — which is when an interface has to stay usable. Building on the published adaptive method of *Mendez Guerra, Barsakcioglu & Farina (2024)*, I added a **closed-loop context head** that decides which detected peaks are true discharges and feeds those decisions back into the adaptation.

> On a **held-out subject, evaluated once with every component frozen**: **87.4%** rate of agreement against **76.9%** for the published method, and **78.6% vs 60.5%** on the fastest ramps. Units tracked at ≥90% agreement rise from 48.6% to 68.1%.
> *Ongoing research. The recordings are simulated HD-sEMG, so ground-truth discharges are known. The hand is not yet driven by the decoded motor units — that is the next stage of the project.*

`MuJoCo` `MyoSuite` `PyTorch` `HD-sEMG` `Attention` `Signal Processing`

---

### 🩺 [Safe Autonomous Catheter Navigation](https://github.com/Santiago23florido/safe-autonomous-catheter-navigation) · Isaac Lab

A physics-based endovascular navigation research environment: an **81-body, 80-DOF flexible catheter** advanced through vascular geometry with contact-force sensing. Wall-contact force is treated as a **constraint rather than another weighted term in the reward**, so the budget is stated in units a clinician can argue with instead of hidden inside a tuned penalty weight. The cost is emitted on a channel structurally separate from the reward.

> *Phase 1 — environment construction. There is no reinforcement learning yet: `_get_rewards()` returns zeros by construction and a test enforces that separation.*

`Isaac Lab` `Isaac Sim` `Python` `PyTorch` `Safe RL / CMDPs`

---

### 📈 [CAGE-NAS — Certified Functional Descent](https://github.com/Santiago23florido/functional-gradient-growth) · NeurIPS 2026 workshop

Uses functional-gradient approximations in the **tangent space of the network** to certify when to keep training parametrically and when to perform a function-preserving expansion, so capacity grows only once the current representation can no longer certify a functional descent step.

> Grown architectures land **above the 99.8th percentile of 76,646 exhaustively enumerated alternatives**, with 0.9575 ± 0.0038 test accuracy over four seeds on the principal synthetic benchmark.

`PyTorch` `Neural Architecture Growth` `Functional Gradients` `Optimization`

---

<details>
<summary><b>More projects</b></summary>

- 🚗 **[Deep-Drive-APEX](https://github.com/Santiago23florido/Deep-Drive-APEX)** — Autonomous navigation on a real robotic vehicle with ROS 2: LiDAR obstacle detection, path planning and trajectory execution, with a Gazebo real-to-sim framework for validation.
- 🌱 **[gromo](https://github.com/Santiago23florido/gromo)** — Contributions to the growing-networks module for PyTorch (Inria TAU).
- 🍼 **[Neonatal Incubator — Dynamic Model & Control](https://github.com/Santiago23florido/Neonatal-Incubator-Dynamic-Model-and-Control)** — Thermodynamic modelling, system identification and discrete-time PID / incremental RST control of a commercial incubator. Published at **IEEE CCAC 2025**.
- 🫁 **[Neonatal Incubator with Apnea Response](https://github.com/Santiago23florido/Neonatal-incubator-with-response-to-apnea-episodes)** — End-to-end central-apnea detection from EMG-derived respiratory signals with CNN–LSTM temporal models and closed-loop corrective stimulation.
- ⚙️ **[Incremental RST Control for a DC Motor](https://github.com/Santiago23florido/Incremental-RST-control-for-DC-motor-with-encoder-design)** — System identification and digital control on real hardware.
- 👁️ **[Robust Image Matching with Local Features](https://github.com/Santiago23florido/Robust-Image-Matching-with-Local-Features)** · **[Vision: Local Features, Bayesian Classification, K-Means](https://github.com/Santiago23florido/Vision_LocalFeatures_BayesianClassification_KMeans)** — Classical computer vision pipelines.
- 🦾 **[SCARA Web-Controlled Robotic Arm](https://github.com/Santiago23florido/Scara-web-controlled-robotic-arm)** — Kinematics, embedded control and a web interface for a physical SCARA arm.

</details>

---

## 🛠️ Tech Stack

<div align="center">

### 🦾 Robot Learning & Simulation
![Isaac Lab](https://img.shields.io/badge/Isaac%20Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/Isaac%20Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1A73E8?style=for-the-badge&logo=googlecolab&logoColor=white)
![MyoSuite](https://img.shields.io/badge/MyoSuite-8E44AD?style=for-the-badge)
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58025?style=for-the-badge&logo=robotframework&logoColor=white)

### 🤖 Machine Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### 🎛️ Control, Modeling & Biosignals
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![HD-sEMG](https://img.shields.io/badge/HD--sEMG-00A98F?style=for-the-badge)
![System ID](https://img.shields.io/badge/System%20Identification-005F73?style=for-the-badge)
![PID / RST](https://img.shields.io/badge/PID%20%2F%20RST%20Control-0A9396?style=for-the-badge)

### ⚙️ Languages, Systems & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-Parallel-blue?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

<sub>Also: Django · FastAPI · Vue.js · Node.js · JavaScript — from earlier embedded-to-web robotics interfaces.</sub>

</div>

---

## 📊 GitHub Statistics

<div align="center">

<img height="170" src="https://streak-stats.demolab.com?user=santiago23florido&theme=tokyonight&hide_border=true&background=0D1117&mode=daily&starting_year=2022&short_numbers=false&cache_bust=20261117" alt="GitHub streak stats" />

</div>

---

## 🎯 Current Goals & Interests

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=700&color=00D9FF&center=true&vCenter=true&width=950&lines=Interfaces+that+read+human+intention+and+act+on+it+reliably;Looking+for+a+PhD+in+Robot+Learning+%2F+Neuromotor+Interfaces" alt="Current goals typing" />

<table>
<tr>
<td width="50%" align="left" valign="top">
<h3>🚀 Current Goals</h3>
<p><b>Neuromotor Interfaces</b></p>
<ul>
  <li>Close the loop: drive the simulated <b>MyoHand</b> directly from decoded motor units.</li>
  <li>Move from simulated HD-sEMG to <b>real recordings</b> during the Imperial placement.</li>
</ul>
<p><b>Robot Learning</b></p>
<ul>
  <li>Push cross-embodiment transfer beyond locomotion, towards <b>manipulation</b>.</li>
  <li>Take the catheter environment from Phase 1 to actual <b>constrained RL</b>.</li>
</ul>
<p><b>Career Target</b></p>
<ul>
  <li>A <b>PhD</b> in robot learning / neuromotor interfaces, starting late 2027.</li>
</ul>
</td>
<td width="50%" align="left" valign="top">
<h3>🔍 Main Interests</h3>
<p><b>Cross-Embodiment & Transfer</b></p>
<ul>
  <li>What has to be true about a skill for it to survive a change of body.</li>
</ul>
<p><b>Biosignals & Motor Intention</b></p>
<ul>
  <li>Decoding motor intention when the signal is ambiguous and the limb is moving.</li>
</ul>
<p><b>Dexterous Manipulation</b></p>
<ul>
  <li>Musculoskeletal and robotic hands, teleoperation, egocentric context.</li>
</ul>
<p><b>Safe & Sample-Efficient RL</b></p>
<ul>
  <li>Constrained MDPs, physics-structured models, learning that grows only when it must.</li>
</ul>
</td>
</tr>
</table>

</div>

---

## 🤝 Let's Collaborate!

<div align="center">

I'm actively looking for:

🎓 **PhD positions** (from late 2027) in:
- Robot Learning & Cross-Embodiment Transfer
- Neuromotor Interfaces & EMG Decoding
- Dexterous Manipulation & Teleoperation

🔬 **Research collaborations** in:
- Humanoid Robotics & Reinforcement Learning in Simulation
- Biosignal Decoding & Musculoskeletal Models
- Safe / Constrained Reinforcement Learning

💬 **Always open to discussing**:
- Technical projects and research ideas
- Reproducing or extending any of the work above

---

### 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiago-florido-gómez-722193232/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:santiago.florido@ensta-paris.fr)

---

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:7DD3FC,100:1E3A8A" width="100%"/>

<img src="https://komarev.com/ghpvc/?username=Santiago23florido&style=for-the-badge&color=blueviolet" alt="Profile views" />

</div>
