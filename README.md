<h1 align="center">Rômulo Tavares Maciel</h1>

<p align="center">
  Computer Engineering undergrad at <b>FURG</b> · Industrial category captain at <b>FBOT</b><br>
  I work on <b>LLMs as robot controllers</b> — prompt engineering, structured JSON output, and measuring whether the model actually got it right.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/r%C3%B4mulo-maciel-178015302/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D" alt="LinkedIn"></a>
  <a href="mailto:rmul.maciel@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://orcid.org/0009-0005-9741-6735"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="http://lattes.cnpq.br/8209814501550767"><img src="https://img.shields.io/badge/Lattes-0A66A6?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Lattes"></a>
</p>

---

### About

I am a third-year Computer Engineering student at the Federal University of Rio Grande (FURG), in southern Brazil, and I captain the industrial category of the **FBOT** robotics team.

Most of my work sits where language models meet real hardware: getting an LLM to emit a plan that a robot can actually execute, constraining that output to a schema instead of hoping for the best, and building the benchmarks that tell me when it fails. I have been programming since 2018 and spent several years on web and mobile before robotics — so I am equally comfortable writing a REST API as I am debugging a ROS 2 node.

- 🔬 Researching LLM task planning at **NAUTEC / C3 — FURG**
- 🤖 Vision-Language-Action policies for bimanual manipulation at **OpenRob**
- 🧪 Constantly testing local models with Ollama to see where small ones break
- 💬 Portuguese (native) · English (advanced)

---

### Featured research

> **LLM Robot Planner: A Modular Closed-Loop Framework for Middleware-Agnostic LLM Task Planning**
> *First author* — submitted to the RoboCup Symposium 2026 (not accepted)
> 📄 [Code](https://github.com/fbot-research/LLM_robot_planner)

A zero-shot cognitive orchestrator that runs entirely on the edge with lightweight models (< 20 GB). It builds prompts dynamically from the robot's state and a registry of typed tools, forces the model's output into a validated JSON action schema, and feeds real execution results back into the next prompt so the model can self-correct.

Evaluated on a 40-task benchmark across four complexity tiers with a 0–3 scoring rubric: **70% perfect execution** on tier 1 and **80% successful completion** on the hardest tier, running a 4B-parameter local model.

---

### Tech

**AI & LLM**

![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=yolo&logoColor=white)

**Languages & backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)

**Robotics & systems**

![ROS](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### FBOT — competitive robotics

Captain of the industrial category (`@Work` / SML) since July 2026, coordinating 24 people.

| Year | Competition | Category | Result |
|:--|:--|:--|:--|
| 2026 | RoboCup | SML | 🏅 4th place |
| 2025 | Brazilian Robotics Competition (CBR) | `@Work` | 🥇 1st place |
| 2025 | RoboCup | `@Work` | 🏅 5th place |
| 2024 | Brazilian Robotics Competition (CBR) | `@Work` | 🥈 2nd place |

---

### Elsewhere

Part of my work lives in organization repositories rather than here — [FBOT Research](https://github.com/fbot-research), [FBOT@Work](https://github.com/FBOTWork) and [OpenRob](https://github.com/OpenRob-FURG).
