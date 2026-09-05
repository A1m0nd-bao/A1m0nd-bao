# A1m0nd-bao

I design and build motion-led web experiences and practical tools at the intersection of interaction design, creative production, and AI agents.

Motion is a major part of how I think about interfaces: not decoration added at the end, but a way to establish hierarchy, explain state, and make an interaction feel understandable.

## What I’ve built

### Motion design and interactive experiences

I use web prototypes and small visual studies to explore how timing, transitions, composition, and feedback shape the feeling of a product. My work ranges from hero-section motion and interactive presentation to reusable Lottie asset workflows.

[Neon Hero Motion Study](https://github.com/A1m0nd-bao/neon-hero-motion-study) focuses on visual rhythm and presentation quality, while [Loci Motion Preview](https://github.com/A1m0nd-bao/loci-motion-preview) turns a growing collection of Lottie JSON files into a searchable, browsable motion library with playback controls, filtering, and Feishu Sheets synchronization.

The goal is always the same: make motion purposeful, easy to review, and practical to reuse in real interfaces.

### Live2D production workflow

In [Morph Live2D Workbench](https://github.com/A1m0nd-bao/live2d-automation-workbench), I built a production workspace for moving a character from reference image to a usable Live2D runtime asset.

It connects a React/Vite workbench with a FastAPI relay and ModelScope See-Through, then tracks the real handoff points: layered PSD, PSD quality review, Cubism `.cmo3`, and compiled `.moc3 + model3.json`. The relay keeps asynchronous jobs durable with SQLite, retries interrupted upstream sessions, validates PSD output, and keeps credentials out of the browser.

### Long-running Android agents

In [OpenGUI](https://github.com/A1m0nd-bao/OpenGUI), I work on an open-source mobile operator system that lets AI operate real Android apps.

The project combines a planning supervisor, an executor graph, Android-side action execution, standby devices, and remote dispatch through Feishu, Telegram, Discord, and REST. The interesting problem is not a short demo loop—it is keeping a task stateful, observable, recoverable, and useful over a long-running workflow.

### Interactive sports data

In [OWCS Champions Clash Predictor](https://github.com/A1m0nd-bao/owcs-champions-clash-predictor), I made a focused static web tool for predicting an OWCS tournament bracket.

The interface turns GSL groups, playoffs, the third-place match, and the final into a click-through experience that automatically advances winners and presents the predicted podium. It is a small project, but it reflects how I like to work: clear state, direct interaction, and no unnecessary complexity.

### Personal blog

[Almond Blog](https://a1m0nd-bao.github.io/Almond_blog/) is my personal blog and a record of my experiments, notes, and web projects. The repository is available at [A1m0nd-bao/Almond_blog](https://github.com/A1m0nd-bao/Almond_blog).

It is part of the same practice: document what I learn, publish small ideas, and use the web itself as a space for visual and interaction experiments.

## How I work

- Start with the feeling and the real workflow, not the feature list.
- Use motion to clarify hierarchy, state, and cause-and-effect.
- Make state and handoffs visible so users know what happens next.
- Keep integrations replaceable and credentials server-side.
- Prefer small, shippable tools over impressive-looking demos.
- Treat deployment, recovery, and documentation as part of the product.

## Tools I use

![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688)
![Vite](https://img.shields.io/badge/Vite-111827?style=flat-square&logo=vite&logoColor=646CFF)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-111827?style=flat-square&logo=github&logoColor=FFFFFF)

## Currently exploring

More reliable creative-production pipelines, better interfaces for AI-assisted work, and agents that can complete real tasks instead of only producing convincing demos.

If you’re working on creative tools, mobile agents, or thoughtful frontend products, [say hello](mailto:bbbbbtr@foxmail.com).
