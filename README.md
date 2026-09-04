<!--
╭──────────────────────────────────────────────────────────────────────────────╮
│  J0hn Vex Coder · Engineering Portfolio                                      │
│  Linux · Infrastructure · Self-Hosting · Automation · Developer Tools        │
╰──────────────────────────────────────────────────────────────────────────────╯
-->

<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:090C10,45:111827,100:172033&text=J0hn%20Vex%20Coder&fontColor=F8FAFC&fontSize=50&fontAlignY=36&desc=Engineering%20software%20close%20to%20the%20system.&descAlignY=58&descSize=17"
  width="100%"
  alt="J0hn Vex Coder"
/>

### SOFTWARE DEVELOPMENT · SYSTEMS · OPEN SOURCE

**Linux engineering, self-hosted infrastructure, automation, observability, and practical developer software.**

<p>
  <a href="https://github.com/johnvexcoder">
    <img src="https://img.shields.io/badge/GitHub-johnvexcoder-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://github.com/johnvexcoder?tab=repositories">
    <img src="https://img.shields.io/badge/Explore-Projects-111827?style=for-the-badge&logo=github&logoColor=white" alt="Projects">
  </a>
  <a href="https://x.com/johnvexcoder">
    <img src="https://img.shields.io/badge/@johnvexcoder-111827?style=for-the-badge&logo=x&logoColor=white" alt="X">
  </a>
  <a href="https://ko-fi.com/johnvexcoder">
    <img src="https://img.shields.io/badge/Support-Open%20Source-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi">
  </a>
</p>

<sub>
<a href="#01--profile">Profile</a> ·
<a href="#02--selected-work">Selected Work</a> ·
<a href="#03--systems-architecture">Architecture</a> ·
<a href="#04--engineering-index">Engineering Index</a> ·
<a href="#05--technology">Technology</a> ·
<a href="#06--principles">Principles</a> ·
<a href="#08--support">Support</a>
</sub>

</div>

<br>

---

# 01 · Profile

<table>
<tr>
<td width="62%" valign="top">

## I build software that stays useful after the demo.

My work sits at the intersection of **applications and systems**: tools that run on Linux, observe infrastructure, automate repetitive operations, expose useful telemetry, manage local resources, or improve how developers interact with their machines.

I am most interested in projects where understanding the underlying system matters just as much as building the interface around it.

That has led me to work across:

- self-hosted infrastructure and observability
- Linux and terminal environments
- host-level telemetry and automation agents
- web, desktop, and CLI applications
- private media and local-first systems

I value software that is **clear to operate, straightforward to inspect, modular enough to extend, and useful enough to keep running**.

</td>
<td width="38%" valign="top">

### Engineering focus

```text
SYSTEMS
Linux · Shell · Hardware

INFRASTRUCTURE
Docker · Proxmox · Telemetry

APPLICATIONS
Web · Desktop · CLI

AUTOMATION
Agents · Monitoring · Tooling

PHILOSOPHY
Useful · Observable · Modular
```

</td>
</tr>
</table>

> **Build the product. Understand the system. Remove the repetition.**

---

# 02 · Selected Work

<div align="center">

### A portfolio of systems, tools, and applications built around real workflows.

</div>

<table>
<tr>
<td width="50%" valign="top">

## 🖥️ HomeLab OS
### Infrastructure Command Center

A self-hosted, NOC-style platform for viewing a homelab as **one operating environment** instead of a collection of disconnected machines and dashboards.

**Engineering surface**

- live server and fleet telemetry
- network topology
- hardware metrics
- alerts and operational views
- Docker visibility
- historical data
- provider-oriented integrations
- administration and control surfaces

**Built with**

`TypeScript` `React` `Vite` `Node.js` `WebSocket` `SQLite`

<br>

**[View HomeLab OS →](https://github.com/johnvexcoder/HomeLab-OS)**

</td>
<td width="50%" valign="top">

## 🤖 HomeLab Agent
### Node Intelligence Layer

A lightweight agent designed to run close to the host and expose information that central infrastructure APIs do not always provide.

**Telemetry surface**

- CPU, memory, and storage
- hardware sensors and temperatures
- SMART health
- Docker information
- kernel and host details
- network statistics
- local system telemetry
- Proxmox-related enrichment

**Built with**

`TypeScript` `Node.js` `Linux` `Docker`

<br>

**[View HomeLab Agent →](https://github.com/johnvexcoder/HomeLab-Agent)**

</td>
</tr>

<tr>
<td width="50%" valign="top">

## 🐧 DistroZSH
### Linux-Native Shell Environment

A framework-free ZSH environment that gives Linux systems a polished, distribution-aware shell while keeping the implementation lightweight and understandable.

**Designed around**

- native ZSH
- distribution-aware presentation
- multiple Linux distributions
- install / uninstall tooling
- configurable layouts
- theme previews
- minimal framework overhead

**Built with**

`ZSH` `Shell` `Linux`

<br>

**[View DistroZSH →](https://github.com/johnvexcoder/DistroZSH)**

</td>
<td width="50%" valign="top">

## 🗜️ CompressMe
### Image Optimization Workspace

A cross-platform image compression application built for both interactive use and repeatable automation.

**Designed around**

- GUI + CLI workflows
- batch compression
- parallel processing
- duplicate detection
- SHA-256 and perceptual hashing
- metadata preservation
- multiple image formats
- history and reporting

**Built with**

`Python` `PySide6` `Pillow` `CLI`

<br>

**[View CompressMe →](https://github.com/johnvexcoder/CompressMe)**

</td>
</tr>

<tr>
<td width="50%" valign="top">

## ⌨️ Python-Keybr
### Terminal Training + Diagnostics

A curses-based typing environment that combines practice, persistent progress, adaptive offline learning, and keyboard diagnostics inside the terminal.

**Designed around**

- multiple training modes
- WPM and accuracy tracking
- persistent statistics
- adaptive practice
- per-letter analysis
- progressive unlocking
- bigram tracking
- visual keyboard diagnostics

**Built with**

`Python` `curses` `CLI`

<br>

**[View Python-Keybr →](https://github.com/johnvexcoder/Python-Keybr)**

</td>
<td width="50%" valign="top">

## 🎬 MovieFlix
### Private Media Platform

A self-hosted media application that turns local or network-attached storage into a complete streaming environment.

**Designed around**

- media library scanning
- movie / TV identification
- metadata and artwork enrichment
- FFprobe analysis
- profiles and authentication
- HTTP range streaming
- subtitles and transcoding
- administration

**Built with**

`Next.js` `TypeScript` `Node.js` `FFmpeg` `SQLite`

<br>

**[View MovieFlix →](https://github.com/johnvexcoder/MovieFlix)**

</td>
</tr>
</table>

<br>

<div align="center">

**[Explore all repositories →](https://github.com/johnvexcoder?tab=repositories)**

</div>

---

# 03 · Systems Architecture

## The HomeLab ecosystem

HomeLab OS and HomeLab Agent are intentionally separate.

The dashboard owns the **operational experience**.  
The agent owns **node-local enrichment**.

```text
┌────────────────────────────────────────────────────────────────────────────┐
│                              HOME LAB OS                                   │
│                                                                            │
│   Fleet · Servers · Topology · Telemetry · Alerts · Administration         │
└────────────────────────────────┬───────────────────────────────────────────┘
                                 │
                         normalized data model
                                 │
               ┌─────────────────┴──────────────────┐
               │                                    │
      ┌────────▼─────────┐                ┌─────────▼─────────┐
      │ Infrastructure   │                │   HomeLab Agent   │
      │ Providers        │                │                   │
      │                  │                │ Node-local        │
      │ Proxmox / APIs   │                │ enrichment        │
      │ VM / LXC state   │                │                   │
      │ Cluster state    │                │ Sensors · SMART   │
      │ Storage / Tasks  │                │ Docker · Network  │
      └──────────────────┘                └─────────┬─────────┘
                                                   │
                             ┌─────────────────────┼────────────────────┐
                             │                     │                    │
                        ┌────▼────┐           ┌────▼────┐         ┌────▼────┐
                        │ Linux   │           │ Docker  │         │Hardware │
                        │ Host    │           │ Engine  │         │ / Disks │
                        └─────────┘           └─────────┘         └─────────┘
```

### Why this split matters

| Layer | Responsibility |
|:--|:--|
| **HomeLab OS** | presentation, fleet state, alerts, topology, workflows |
| **Infrastructure providers** | authoritative platform / infrastructure data |
| **HomeLab Agent** | host-only telemetry and machine-local enrichment |
| **Linux / Docker / hardware** | raw operating environment |

The result is a system where richer telemetry can be added without forcing the dashboard to become tightly coupled to one operating system, one hypervisor, or one hardware layout.

---

# 04 · Engineering Index

<table>
<tr>
<td align="center" width="25%">

### SYSTEMS

Linux  
Shell environments  
Hardware telemetry  
Diagnostics

</td>
<td align="center" width="25%">

### INFRASTRUCTURE

Self-hosting  
Docker  
Proxmox  
Monitoring

</td>
<td align="center" width="25%">

### AUTOMATION

Agents  
Installers  
Background services  
Operational tooling

</td>
<td align="center" width="25%">

### APPLICATIONS

Web platforms  
Desktop tools  
CLI software  
Media systems

</td>
</tr>
</table>

### Current development lines

```text
┌────┬────────────────┬────────────────────────────────────────────────────┐
│ 01 │ HomeLab OS     │ Infrastructure visibility and operations           │
│ 02 │ HomeLab Agent  │ Host telemetry and system enrichment               │
│ 03 │ DistroZSH      │ Lightweight Linux shell experience                 │
│ 04 │ Python-Keybr   │ Terminal training and keyboard diagnostics         │
│ 05 │ CompressMe     │ Image optimization for users and automation        │
│ 06 │ MovieFlix      │ Private media built around local / NAS storage     │
└────┴────────────────┴────────────────────────────────────────────────────┘
```

---

# 05 · Technology

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,ts,js,bash,c,cpp,cs&perline=7" alt="Languages">

### Application Engineering

<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,vite,tailwind,qt&perline=7" alt="Application engineering">

### Infrastructure & Platform

<img src="https://skillicons.dev/icons?i=linux,docker,git,github,cloudflare,gcp,nginx&perline=7" alt="Infrastructure and platform">

<br>

<sub><strong>The problem determines the stack.</strong> Technologies are tools, not the identity of the project.</sub>

</div>

---

# 06 · Principles

<table>
<tr>
<td width="33%" valign="top">

### 01 / Utility

**Useful over impressive.**

A project should solve a workflow or remove friction, not exist only to demonstrate a technology.

</td>
<td width="33%" valign="top">

### 02 / Clarity

**Understand the system.**

Good software makes behavior observable and important decisions explainable.

</td>
<td width="33%" valign="top">

### 03 / Automation

**Remove repetition.**

Repeated operations eventually become scripts, tools, agents, or better interfaces.

</td>
</tr>

<tr>
<td width="33%" valign="top">

### 04 / Architecture

**Keep boundaries deliberate.**

Collection, presentation, integrations, storage, and platform-specific logic should have clear responsibilities.

</td>
<td width="33%" valign="top">

### 05 / Ownership

**Control the important layers.**

Self-hosting is valuable when it improves control over deployment, data, and the underlying system.

</td>
<td width="33%" valign="top">

### 06 / Iteration

**Ship, observe, refine.**

Useful software is shaped by real usage, debugging, feedback, and repeated improvement.

</td>
</tr>
</table>

---

# 07 · Operating Model

```text
           DISCOVER
      understand the problem
               │
               ▼
            BUILD
      create the smallest
       useful system
               │
               ▼
           OBSERVE
      expose behavior and
          failure modes
               │
               ▼
           IMPROVE
      remove friction and
      tighten architecture
               │
               ▼
          AUTOMATE
      make repeated work
         disappear
               │
               └──────────────────────► iterate
```

### The standard I aim for

A project is not finished because the interface renders or the command succeeds.

It becomes valuable when someone can **understand it, run it, operate it, recover from problems, and extend it without fighting the architecture**.

---

# GitHub Activity

<div align="center">

<img
  src="https://github-readme-stats.vercel.app/api?username=johnvexcoder&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&include_all_commits=true"
  height="175"
  alt="GitHub statistics"
/>

<img
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=johnvexcoder&layout=compact&hide_border=true&theme=transparent&langs_count=8"
  height="175"
  alt="Top languages"
/>

<br>

<img
  src="https://streak-stats.demolab.com?user=johnvexcoder&theme=transparent&hide_border=true"
  alt="GitHub contribution streak"
/>

</div>

---

# 08 · Support

## Open source should stay useful.

I publish my main projects in public because software becomes more valuable when people can inspect it, learn from it, run it, adapt it, and improve it.

If something I built has saved you time or made a system easier to operate, you can support continued development here:

<p>
  <a href="https://ko-fi.com/johnvexcoder">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support me on Ko-fi">
  </a>
</p>

<sub>Based in the Philippines · Support is open worldwide.</sub>

---

# Connect

<p>
  <a href="https://github.com/johnvexcoder">
    <img src="https://img.shields.io/badge/GitHub-18181B?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://x.com/johnvexcoder">
    <img src="https://img.shields.io/badge/X-18181B?style=flat-square&logo=x&logoColor=white" alt="X">
  </a>
  <a href="https://ko-fi.com/johnvexcoder">
    <img src="https://img.shields.io/badge/Ko--fi-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white" alt="Ko-fi">
  </a>
</p>

---

<div align="center">

### ENGINEER THE SYSTEM · SHIP THE TOOL · IMPROVE THE WORKFLOW

<sub>
J0hn Vex Coder · Open Source Engineering · Linux · Self-Hosted Systems
</sub>

<br><br>

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:172033,50:111827,100:090C10&height=120&section=footer"
  width="100%"
  alt=""
/>

</div>

<!--
Maintenance notes:
- Keep project descriptions aligned with repository reality.
- Update "Current development lines" as priorities change.
- Avoid vanity badges and unsupported claims.
- The README should still communicate value if external stat services fail.
-->
