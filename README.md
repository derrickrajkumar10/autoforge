<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=AutoForge&fontSize=64&fontColor=fff&animation=twinkling&fontAlignY=38&desc=A%20multi-agent%20AI%20system%20that%20plans%20and%20codes&descAlignY=62&descSize=18"/>
</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=3776AB)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent%20AI-0D1117?style=for-the-badge&logo=openai&logoColor=7C3AED)
![License](https://img.shields.io/badge/License-MIT-0D1117?style=for-the-badge)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## ⚙️ About

AutoForge is a multi-agent AI framework where specialised agents collaborate to plan and generate code autonomously.

A Router decides who acts next. A Planner figures out what needs to be done. A Code Agent writes it. Clean, modular, and built to be extended.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## 🧩 Architecture

```
main.py
  └── RouterAgent         → decides which agent runs next
        ├── PlannerAgent  → breaks down tasks into steps
        └── CodeAgent     → generates code from the plan
```

Each agent is independently modular and extensible.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## ✨ Features

- 🔀 **Intelligent routing** — Router dynamically selects the right agent for each step
- 🗺️ **AI planning** — Planner decomposes tasks before any code is written
- 💻 **Code generation** — Code Agent translates plans into working code
- 🔌 **Modular by design** — drop in new agents, tools, or system prompts easily
- 🐍 **Pure Python** — no heavy frameworks, minimal dependencies

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## 🚀 Getting Started

```bash
git clone https://github.com/derrickrajkumar10/autoforge.git
cd autoforge

pip install -r requirements.txt

python main.py
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## 📁 Project Structure

```
autoforge/
├── agents/
│   ├── planner.py      # PlannerAgent — task decomposition
│   ├── router.py       # RouterAgent — orchestration logic
│   └── code_agent.py   # CodeAgent — code generation
├── system/             # System prompts and config
├── tools/              # Tool integrations
├── main.py             # Entry point
└── requirements.txt
```

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
</div>
