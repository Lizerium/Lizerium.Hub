<h1 align="center">🌌 Lizerium Hub 🌌</h1>

<p align="center">
  Central map of directions, layers, and transitions within the Lizerium ecosystem
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Language: </strong>
  
  <a href="./README.ru.md" style="color: #F5F752; margin: 0 10px;">
    🇷🇺 Russian
  </a>
  | 
  <span style="color: #0891b2; margin: 0 10px;">
    ✅ 🇺🇸 English (current)
  </span>
</div>

---

> [!NOTE]
> This project is part of the **Lizerium** ecosystem within the organization:
>
> - [`Lizerium`](https://github.com/Lizerium)

## Purpose

`Lizerium.Hub` is the **navigation and architectural center** of the **Lizerium** ecosystem.

If the organization’s main page answers the question:

> **"What is Lizerium?"**

then this repository answers:

> **"How is it structured and where to go next?"**

---

## What’s Inside the Hub

This repository exists to:

- provide visibility into the main engineering directions
- define responsibility boundaries between layers
- enable quick navigation across architectural branches
- present the ecosystem as a connected system rather than a set of isolated repositories

---

## Navigation Levels

The Lizerium ecosystem is divided into several major directions.

Each direction has its own **structural index** (`*.Structs`), which leads deeper into domain-specific working repositories.

---

## Direction Map

### 🎮 Game Direction

Game data, formats, logical representations of resources, and structural game layers.

→ [`Lizerium.Game.Structs`](https://github.com/Lizerium/Lizerium.Game.Structs)

---

### 🚀 Unity Direction

Game runtime, ECS, visual subsystems, effects, in-game logic, and technical Unity branches.

→ [`Lizerium.Unity.Structs`](https://github.com/Lizerium/Lizerium.Unity.Structs)

---

### 🖥 Servers & Infrastructure

Backend components, networking systems, infrastructure modules, launchers, and runtime services.

→ [`Lizerium.Software.Structs`](https://github.com/Lizerium/Lizerium.Software.Structs)

---

### 🧰 Tools

Editors, parsers, libraries, utility tools, and engineering support systems.

→ [`Lizerium.Tools.Structs`](https://github.com/Lizerium/Lizerium.Tools.Structs)

---

### 🧪 Frameworks & Quality Control

Testing systems, validation pipelines, integrity checks, and automated control layers.

→ [`Lizerium.Frameworks.Structs`](https://github.com/Lizerium/Lizerium.Frameworks.Structs)

---

## Architecture Diagram

```text
Lizerium
├── Game
│   └── Lizerium.Game.Structs
│
├── Unity
│   └── Lizerium.Unity.Structs
│
├── Software
│   └── Lizerium.Software.Structs
│
├── Tools
│   └── Lizerium.Tools.Structs
│
└── Frameworks
    └── Lizerium.Frameworks.Structs
```

---

## How to Navigate the Ecosystem

Recommended exploration path:

1. **Organization main page** — general understanding of the project
2. **`Lizerium.Hub`** — overview of directions
3. **`*.Structs` repository** — structure of a specific layer
4. **Working repositories** — actual implementations

---

## Organizational Principle

Lizerium is not designed as a linear collection of projects, but as a **multi-layered engineering system**.

Therefore, the architecture is structured across levels:

- ecosystem level
- direction level
- subsystem level
- concrete tool / runtime component level

---

## Note

This repository is not a primary implementation.

It serves as a **central map**, providing a clear view of the overall structure of the entire ecosystem.
