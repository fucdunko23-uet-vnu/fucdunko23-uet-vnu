# Hi there, I'm To Vu Phuc Dang (Dang) 👋
### 🎮 Game & AI Engineer | 🛰️ Computer Engineering Student @ VNU-UET
I like building things from scratch — engines, pipelines, whatever the project needs instead of reaching for the closest off-the-shelf tool. Right now I'm in the final round of **Prompt to Play 2026**, and separately trying to land a **GSoC 2026** slot with **OSGeo**.
📄 **[Download my Resume →](https://raw.githubusercontent.com/fucdunko23-uet-vnu/fucdunko23-uet-vnu/main/assets/TVPD_Resume.pdf)**
---
### 🎮 Featured Project: AEGIS — The Adaptive Machine
*A 2D boss-rush where the boss actually learns from how you fight. After each round, an LLM reads your combat data and rewrites the boss — new stats, new attacks, tuned to whatever you did to beat it last time.*
- **AI Feedback Loop:** Every fight, I track dodge rate, distance kept, damage split, positioning. That gets sent to Groq's Llama-3.3-70B, which returns a `BossConfig` — and the next fight is genuinely different, not just "bigger numbers."
- **Engine built from zero:** Physics, rendering, the whole game loop — all hand-rolled on raw Canvas 2D. No Phaser, no Unity, mostly because I wanted to understand every layer of what's happening.
- **Boss AI:** An FSM with a weighted-roulette skill selector, ten tiers of "awareness" — predictive aiming, gravity-drop prediction, combo chaining. I wanted the difficulty to emerge from the fight, not from a level-scaling spreadsheet.
- 🎮 **[Play it live →](https://aegis-boss-rush.onrender.com/)** *(runs on a free-tier server, so the first load can take 30–50s to wake up)*
- 🔗 **[Repo →](https://github.com/fucdunko23-uet-vnu/aegis-boss-rush)**
### 🎥 Gameplay Demo
[![AEGIS Gameplay Demo](https://img.youtube.com/vi/_uivdKRABqg/maxresdefault.jpg)](https://youtu.be/_uivdKRABqg)
---
### 🛠️ Technical Arsenal
- **Game Dev:** TypeScript, Next.js/React, Canvas 2D, real-time systems, game AI (FSM, weighted decision-making), LLM integration
- **Programming Languages:** Python, C++, Java, SQL, Bash
- **Geospatial & AI:** GDAL, NumPy, PyGRASS, Xarray, Dask, PyTorch Geometric
- **Tools:** Linux (Ubuntu/WSL2), Docker, Git/GitHub, LaTeX
---
### 🏆 Professional Proofs
- **Research:** Handling 40GB+ satellite imagery for population-density modeling at **FIMO Lab**.
- **Leadership:** Vice Head of Incubation Department @ **SOICT Innovation Club**.
- **HackerRank:** 🌟🌟🌟🌟 (4-Star) in **SQL** and **Linux**.
<p align="left">
  <a href="https://www.hackerrank.com/fucdunko23">
    <img src="https://hackerrank-badges.vercel.app/api/?username=fucdunko23&badge=sql" alt="SQL Badge" height="120">
  </a>
</p>
---
### 📈 Current Hustle: GSoC 2026
- **OSGeo:** Refactoring `r.learn.ml2` for $O(1)$ memory scalability using PyGRASS and Dask (Selected).
- **MLLAM:** Implementing Icosahedral Hierarchical GNNs for global weather forecasting.
---
📫 **Connect with me:**
- Email: [24020433@vnu.edu.vn](mailto:24020433@vnu.edu.vn) | [fucdunko23@gmail.com](mailto:fucdunko23@gmail.com)
- LinkedIn: [linkedin.com/in/to-vu-phuc-dang-07821a353/](https://linkedin.com/in/to-vu-phuc-dang-07821a353/)
