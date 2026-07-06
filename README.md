# Hi, I'm David 👋
**Systems & Robotics CS Student | Bridging C++ Performance with Python Logic**

I'm a Computer Science student at the University of Florida (Class of 2029). While I spend my days as a Research Assistant building BEV perception pipelines for autonomous driving, my true love for coding started with gaming. I build to automate the boring parts of games and optimize the fun and competitive parts. 

Whether it's writing Python scripts to autonomously mine in Minecraft, engineering a C++ spatial clustering engine to process millions of blocks, or grinding advanced LeetCode patterns, I thrive on solving complex problems. I love bridging high-level logic with low-level performance. When I'm not coding or studying, you can probably find me playing soccer with friends, gaming, or watching anime.

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

### Frameworks & Libraries
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![STL](https://img.shields.io/badge/STL-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![pybind11](https://img.shields.io/badge/pybind11-FFD21E?style=for-the-badge&logo=cplusplus&logoColor=black)

### Developer Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 💻 Featured Engineering

### Autonomous Vehicle Vision Pipeline (UF V2A2 Lab)
**Tech:** PyTorch, ROS 2, Python, Docker  
A real-time vision pipeline engineered for the LIMO platform integrating U-Net models to process raw LiDAR and depth camera data.  
[🎥 Watch Demo](#) | [🔗 GitHub](https://github.com/sh1ftedwastaken/V2A2-LAB)

<details>
<summary><b>⚙️ View Architecture & Impact</b></summary>
<ul>
  <li>Refined segmentation accuracy to <strong>0.9439 mIoU</strong> by deploying and evaluating advanced hybrid loss functions (Cross Entropy, Focal, Lovasz-Softmax, Jaccard).</li>
  <li>Developed a Bird’s Eye View (BEV) transformation node to warp segmented masks, establishing the spatial foundation for autonomous navigation and teleop control.</li>
  <li>Engineered safety-critical Python control scripts, including automated emergency braking and Docker-based remote hardware deployment.</li>
  <li>Currently working on the autonomous driving pipeline, which contains a fully working line-following logic and partial overtaking obstacle logic.</li> 
</ul>
</details>

<br>

### Autonomous Voxel-Environment Navigation Agent (v2.0)
**Tech:** Python, A* Algorithm, Graph Traversal, Modular Architecture  
A dual-layer robotics pipeline built to autonomously navigate procedural 3D environments while dynamically detecting and avoiding hazards.  
[🎥 Watch Demo](https://youtu.be/IdFy5w9tKBE) | [🔗 GitHub](https://github.com/sh1ftedwastaken/Minecraft-AutoMiner-BOT)

<details>
<summary><b>⚙️ View Architecture & Impact</b></summary>
<ul>
  <li>Implemented A* Pathfinding and Frontier Expansion algorithms coupled with a heuristic clustering engine, reducing time complexity from $O(r^3)$ to $O(r^2)$ per expansion and cutting redundant API calls by ~75%.</li>
  <li>Architected a fault-tolerant recovery system monitoring 10+ variables (e.g., lava proximity, durability) to trigger autonomous safety protocols.</li>
  <li>Refactored a monolithic codebase to isolate sensing and decision-making modules for improved testability and scaling.</li>
</ul>
</details>

<br>

### Voxel Spatial Analysis & Data Pipeline Engine
**Tech:** C++20, Python, STL, nlohmann/json  
A high-performance hybrid architecture utilizing C++ for core spatial analysis and Python for high-level logic, designed to scan millions of data points rapidly.  
[🎥 Watch Demo](#) | [🔗 GitHub](https://github.com/sh1ftedwastaken/Minecraft-Base-Finder)

<details>
<summary><b>⚙️ View Architecture & Impact</b></summary>
<ul>
  <li>Built an OOP-based C++ spatial clustering engine utilizing hash-based containers and DFS-based flood fill algorithms to process datasets at <strong>2.5M+ blocks/second</strong>.</li>
  <li>Engineered a cross-language JSON serialization pipeline to minimize computational overhead between the C++ core and Python I/O layer.</li>
  <li>Developed a modular Python data management layer featuring a parameterized 7-command CLI for custom file handling and data retrieval.</li>
</ul>
</details>

<br>

### Object-Oriented Minesweeper Engine
**Tech:** C++, STL, Algorithmic Design  
A performance-optimized Minesweeper application focusing on strict memory management and recursive zero-guess solving algorithms.  
[🎥 Watch Demo](#) | [🔗 GitHub](https://github.com/sh1ftedwastaken/Minesweeper)

<details>
<summary><b>⚙️ View Architecture & Impact</b></summary>
<ul>
  <li>Constructed a high-efficiency engine utilizing OOP and a recursive flood-fill algorithm for automated tile clearance.</li>
  <li>Engineered manual memory management protocols utilizing pointers and destructors to ensure stable execution and zero memory leaks.</li>
  <li>Implemented 3BV calculation and advanced pattern recognition (1-2-1, 1-2-2-1) for optimal flagging strategies.</li>
</ul>
</details>

---

## 🌱 Currently Learning & Building

* **Ping Optimization Project: ** Designing a program to bypass operating system algorithms and optimize network paths to reduce local latency in competitive games.
* **Family Business Infrastructure:** Architecting a full-stack logistics and web presence platform for my family reseller business.
* **Competitive Programming:** Mastering advanced Data Structures and Algorithms (Dynamic Programming, Monotonic Stacks, Graph Theory). Currently at **100+ LeetCode problems solved.**

---

## ⚡ Quick Facts

* **Trilingual:** Native in Spanish, Fluent in English, Conversational in Chinese.
* **Logistics:** Managed daily operations, customer attention, and finances for two high-volume restaurants for 6+ years.
* **Leadership:** Led a 100+ students house team to a 1st Place Copa Cumbre Championship after a 5-year losing streak.
* **Academic:** 3.93 Overall GPA | 4.0 Technical GPA.

---

## 📊 Developer Analytics

<div align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=sh1ftedwastaken&theme=dark&hide=prs,issues&count_private=false&show_icons=&hide_border=true" alt="GitHub Stats" height="180" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sh1ftedwastaken&theme=dark&hide_border=true" alt="GitHub Streak" height="180" />
</div>

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/davidzl)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@sh1ftedwastaken)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sh1ftedwastaken)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://sh1ftedwastaken.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:davidzouli@ufl.edu)
