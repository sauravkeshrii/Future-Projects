# 📚 Robotics Publications – Study Notes

A curated collection of influential robotics publications, spanning security, modular hardware, reinforcement learning, and more.  
Each entry includes a brief description, why it matters, key takeaways, and relevant tags.

---

## 1. 🧩 robot_blockly: programming ROS with blocks  
**ROSCon 2016 · Oct 8, 2016**  
*Easiest entry point – visual programming for ROS.*

**What it is**  
A ROS package that lets you create robot behaviours by snapping together graphical blocks (like Scratch or Blockly). It hides the complexity of ROS, making robot programming accessible to beginners.

**Why it matters**  
Learning ROS traditionally takes weeks. robot_blockly lowers the barrier, allowing anyone with basic logic skills to prototype robot behaviours.

**Key takeaway**  
Visual programming can democratise robotics – you can build simple ROS apps without writing a single line of code.

`#ROS` `#visual-programming` `#education`

---

## 2. 📖 Dissecting Robotics – historical overview and future perspectives  
**Apr 27, 2017**  
*A literature‑style review of where robotics came from and where it’s going.*

**What it is**  
A retrospective of major milestones in robotics over the last decades, discussing the shift from isolated industrial arms to connected, intelligent machines. It highlights the need for reduced integration time and common hardware standards.

**Why it matters**  
Understanding the past helps you see why modern robotics is moving toward modularity, interoperability, and AI integration.

**Key takeaway**  
Robotics is undergoing its own industrial revolution – the challenges today (cost, integration, standards) are echoes of earlier tech waves.

`#history` `#trends` `#modularity`

---

## 3. 🚁 "Linux Drones & the App Store for Drones"  
**GoTo Amsterdam 2015 Conference · Jun 19, 2015**  
*A talk about bringing an app‑store model to drones.*

**What it is**  
A presentation on Linux‑based drones running ROS, and the vision of a marketplace where developers can share, sell, and download drone algorithms – much like a smartphone app store.

**Why it matters**  
It foreshadows the trend of “software‑defined drones” and the commercialisation of robotic algorithms.

**Key takeaway**  
The idea of an “app store for robots” shifts robotics from monolithic products to platforms where third‑party developers can innovate.

`#drones` `#ROS` `#marketplace`

---

## 4. 🛸 Towards an Open Source Linux autopilot for drones  
**LibreCon 2014 · Nov 12, 2014**  
*A hands‑on project to build a Linux‑based autopilot for multiple vehicle types.*

**What it is**  
The paper describes turning the APM (ArduPilot) autopilot into a Linux‑compatible system by creating a Hardware Abstraction Layer (HAL). It supports copters, rovers, and planes.

**Why it matters**  
Most autopilots run on bare‑metal or RTOS. Bringing Linux opens the door to using high‑level libraries, vision algorithms, and ROS on board.

**Key takeaway**  
You can run a full Linux OS on a drone and still achieve real‑time control with the right abstraction layer – a stepping stone to more intelligent autonomous vehicles.

`#autopilot` `#Linux` `#HAL` `#drones`

---

## 5. 🎮 Extending the OpenAI Gym for robotics: a toolkit for reinforcement learning using ROS and Gazebo  
**Aug 19, 2016**  
*Combining RL with realistic simulation.*

**What it is**  
An extension of OpenAI Gym that connects to ROS and Gazebo, allowing reinforcement learning agents to be trained in physics‑based robotic simulations. It includes benchmarking with Q‑Learning and Sarsa.

**Why it matters**  
It bridges the gap between toy RL problems (like CartPole) and real robot learning, providing a standardised way to compare algorithms in realistic environments.

**Key takeaway**  
You can use the same Gym interface you know from ML courses to train robots in Gazebo – a perfect setup for experimenting with RL on robotic tasks.

`#reinforcement-learning` `#Gazebo` `#ROS` `#OpenAI`

---

## 6. 🌊 Analysis and Management of Water Bodies by Means of Terrestrial Video‑Imagery Techniques: Zeus‑Fluem Project  
**International Water Association, Granada (Spain) · 2011**  
*Environmental monitoring using computer vision – a non‑robotics project but still relevant.*

**What it is**  
A project that uses terrestrial video imagery to monitor and analyse water bodies (rivers, lakes). It involves image processing to extract meaningful data for water management.

**Why it matters**  
It shows how computer vision can be applied outside robotics – and the techniques (image analysis, feature extraction) transfer directly to robotic perception.

**Key takeaway**  
Vision algorithms are universal – the same methods used here can be adapted for robot navigation, object detection, or environmental monitoring robots.

`#computer-vision` `#environmental` `#monitoring`

---

## 7. 🔍 aztarna, a footprinting tool for robots  
**Dec 27, 2018**  
*Your first step into robot security – scanning for robot footprints.*

**What it is**  
Aztarna is an open‑source tool that scans networks to identify robots and their components (e.g., ROS masters, SROS nodes, industrial robot controllers). It helps security researchers map out robot installations.

**Why it matters**  
Robots are increasingly connected, yet many lack basic security. Aztarna lets you discover what’s out there – the first step in any security assessment.

**Key takeaway**  
Footprinting is the reconnaissance phase of hacking. With aztarna, you can learn to identify robot‑specific services and understand their exposure.

`#security` `#footprinting` `#ROS` `#opensource`

---

## 8. 🏴‍☠️ Robotics CTF (RCTF), a playground for robot hacking  
**Oct 1, 2018**  
*Hands‑on challenges to practice robot security.*

**What it is**  
An online Capture‑The‑Flag platform with nine scenarios where you can hack virtual robots from your browser. The scenarios mimic real‑world setups (e.g., exploiting ROS topics, breaking into robot interfaces).

**Why it matters**  
Theory is not enough – RCTF gives you a safe, legal environment to practice attacking and defending robotic systems.

**Key takeaway**  
You can learn robot hacking by doing: exploit misconfigured ROS networks, intercept unencrypted messages, and understand why security by obscurity fails.

`#CTF` `#hacking` `#security` `#ROS`

---

## 9. 📊 Towards an open standard for assessing the severity of robot security vulnerabilities – RVSS  
**Aug 1, 2018**  
*A scoring system tailored for robot vulnerabilities.*

**What it is**  
The Robot Vulnerability Scoring System (RVSS) adapts the common CVSS to include robot‑specific factors: safety impact, downstream consequences, third‑party library issues, and environmental variables (e.g., time since disclosure).

**Why it matters**  
A vulnerability in a robot can cause physical harm, which CVSS doesn’t capture well. RVSS provides a more accurate severity score for roboticists and security teams.

**Key takeaway**  
When assessing robot risks, you must consider safety and the physical world – not just data confidentiality.

`#security` `#scoring` `#RVSS` `#safety`

---

## 10. 🛡️ Introducing the Robot Security Framework (RSF) – a standardized methodology to perform security assessments in robotics  
**arXiv:1806.04042 · Jun 12, 2018**  
*A structured way to audit robots from top to bottom.*

**What it is**  
RSF breaks down a robot into four layers: Physical, Network, Firmware, and Application. For each layer it defines what to check, what tools to use, and how to interpret results. It’s a holistic methodology.

**Why it matters**  
Security assessments are often ad‑hoc. RSF gives you a checklist and a common language to ensure you haven’t missed anything – from bolts to binaries.

**Key takeaway**  
Think of a robot as a stack – securing it requires examining hardware, comms, low‑level code, and high‑level apps separately, but also understanding how they interact.

`#security` `#framework` `#audit` `#RSF`

---

## 11. 🧩 An information model for modular robots: the Hardware Robot Information Model (HRIM)  
**Feb 6, 2018**  
*Making robot hardware plug‑and‑play.*

**What it is**  
HRIM is a standardised way to describe robot hardware components (sensors, actuators, etc.) so they can be automatically discovered and integrated. It’s like USB‑plug‑and‑play, but for robot parts.

**Why it matters**  
Today, mixing parts from different vendors is a nightmare. HRIM enables interoperability, letting you swap a motor from company A with one from company B without rewriting code.

**Key takeaway**  
A common information model is the foundation for a true “robot component ecosystem” – it turns hardware into software‑defined objects.

`#modular-robotics` `#interoperability` `#HRIM` `#hardware`

---

## 12. 🔌 Introducing H‑ROS: the Hardware Robot Operating System  
**ROSCon 2016 · Oct 8, 2016**  
*First glimpse of a hardware abstraction layer for ROS.*

**What it is**  
H‑ROS is an infrastructure (hardware + software) that makes robot components natively speak ROS. It allows components to be dynamically added/removed and to self‑describe their capabilities.

**Why it matters**  
It’s a radical shift from today’s bespoke robot builds. With H‑ROS, building a robot becomes as simple as assembling LEGO – each part announces what it is and how to use it.

**Key takeaway**  
The future of robotics lies in modular, interoperable hardware that behaves like software services – discoverable, replaceable, and reusable.

`#H-ROS` `#modular-robotics` `#ROS` `#hardware`

---

## 13. ⚙️ The shift in the robotics paradigm – the Hardware Robot Operating System (H‑ROS); an infrastructure to create interoperable robot components  
**NASA/ESA Conference on Adaptive Hardware and Systems (AHS 2017) · Jun 21, 2017**  
*A deeper dive into the H‑ROS architecture and its implementation.*

**What it is**  
This paper expands on the H‑ROS concept, detailing how components maintain an internal model of the robot and how reconfiguration happens on the fly. It includes experimental results with real hardware.

**Why it matters**  
It proves that the H‑ROS vision is not just a slide deck – it works in practice, enabling robots to literally swap arms or sensors while running.

**Key takeaway**  
Hardware modularity + ROS 2 = robots that can adapt their own morphology. This is a stepping stone to self‑reconfiguring robots.

`#H-ROS` `#modularity` `#reconfiguration` `#ROS2`

---

## 14. 🧠 Towards self‑adaptable robots: from programming to training machines  
**Feb 12, 2018**  
*Moving from explicit programming to AI‑driven adaptation.*

**What it is**  
The authors argue that hardware modularity + AI allows robots to adapt to new tasks without being reprogrammed. Instead of coding, you train the robot (using techniques like reinforcement learning) to produce robust behaviours even with noisy sensors.

**Why it matters**  
It’s a paradigm shift: robots become “trainable” rather than “programmable”. This makes them more flexible and easier to deploy in unstructured environments.

**Key takeaway**  
Combine modular hardware with learning algorithms, and you get machines that can figure out how to use their own body to achieve a goal – no manual tuning required.

`#AI` `#self-adaptable` `#modular-robots` `#learning`

---

## 15. 🏛️ Hierarchical Learning for Modular Robots  
**Feb 11, 2018**  
*Teaching a robot multiple tasks by switching configurations.*

**What it is**  
A hierarchical neural network approach where a robot learns to select both a motor primitive and a body configuration (e.g., 3‑DoF vs. 4‑DoF arm) to achieve different targets. The network is trained in simulation and transferred to a real robot.

**Why it matters**  
It demonstrates that a single policy can handle multiple robot morphologies and tasks – a key step toward robots that can reconfigure themselves and still know how to act.

**Key takeaway**  
Hierarchical learning lets a robot reason at two levels: “what limb should I use?” and “how should I move it?”. This is essential for modular, adaptable machines.

`#hierarchical-RL` `#modular-robots` `#transfer-learning`

---

## 16. 📈 Evaluation of Deep Reinforcement Learning Methods for Modular Robots  
**Feb 7, 2018**  
*Pushing DRL from simulation to reality on modular hardware.*

**What it is**  
A framework that applies state‑of‑the‑art DRL algorithms (like DDPG, PPO) to modular robots. It uses ROS and Gazebo for training, then transfers the learned policy to a physical robot, addressing the sim‑to‑real gap. It also shows that adding an extra DoF does not hinder learning.

**Why it matters**  
It validates that deep RL can be used on real modular robots, and that the learned policies are robust enough to transfer from simulation. It also explores accelerating simulation time to speed up training.

**Key takeaway**  
DRL is not just for games – it can control real robot arms with multiple degrees of freedom, and modularity does not complicate learning. The techniques to bridge simulation and reality are becoming practical.

`#deepRL` `#sim-to-real` `#modular-robots` `#Gazebo`

---

## 🧾 License & Usage

These notes are for personal study and reference. All publications are the work of Alejandro Hernandez Cordero and his collaborators. For more details, visit his [LinkedIn profile](https://www.linkedin.com/in/ahcorde/).

⭐ **Feel free to star this repo if you find it useful!**
