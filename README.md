<!-- Header: a live 2D heat-equation simulation (assets/heat-banner.svg) -->
<p align="center">
  <img src="assets/heat-banner.svg" alt="Animated heat diffusion banner — Ibrahim Parvez" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/ibrahim-parvez">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=76B900&center=true&vCenter=true&width=720&lines=Writing+CUDA+kernels+that+make+simulations+fly;Building+software+researchers+actually+use;Heading+toward+Cloud+%2B+High-Performance+Computing" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ibrahimparvez/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn"/></a>
  <a href="mailto:parvezi@mcmaster.ca"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=76b900" alt="Email"/></a>
  <a href="https://mrsi.mcmaster.ca"><img src="https://img.shields.io/badge/mrsi.mcmaster.ca-0d1117?style=for-the-badge&logo=googlechrome&logoColor=fbb41a" alt="MRSI website"/></a>
  <img src="https://komarev.com/ghpvc/?username=ibrahim-parvez&style=for-the-badge&color=76b900&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<!-- Terminal card styled like nvidia-smi (assets/nvidia-smi.svg) -->
<p align="center">
  <img src="assets/nvidia-smi.svg" alt="nvidia-smi style card: roles and active projects" width="92%"/>
</p>

---

## `$ whoami`

I'm a **Computer Science (Honours, Co-op)** student at **McMaster University**, graduating **April 2027**. I'm also a **Research Software Engineer** for McMaster's Faculty of Science. I like software that is **fast, correct, and actually used**, and I'm steering toward **cloud and high-performance computing**: GPUs, parallel systems, and the infrastructure that runs them at scale.

- ⚡ **GPU computing:** NVIDIA DLI certified in *Accelerated Computing with Modern CUDA C++*; now writing my own CUDA solvers
- 🔬 **Research software:** I build tools that turn hours of manual lab work into a single click
- 🏗️ **Systems foundation:** Operating Systems, Concurrent Systems, Computer Architecture, Networks & Security, Scientific Computing
- 🎯 **Next:** a master's in cloud/HPC, then multi-GPU, distributed, and cloud-native compute

---

## 🛰️ Path to Cloud HPC

```mermaid
flowchart LR
    subgraph DONE["✅ Foundations"]
        A[Scientific Computing<br/>Runge-Kutta · error analysis]
        B[OS · Concurrency<br/>Computer Architecture]
        C[NVIDIA DLI<br/>CUDA C++]
    end
    subgraph NOW["⚙️ Building now"]
        D[GPU Heat Diffusion<br/>shared-memory tiling]
        E[Rookery frontend<br/>Next.js · React]
        F[MRSI web CMS<br/>PHP]
    end
    subgraph NEXT["🚀 Next"]
        G[Multi-GPU · MPI<br/>domain decomposition]
        H[Kubernetes · Terraform<br/>autoscaling GPU jobs]
        I[Master's in<br/>Cloud / HPC]
    end
    A --> D
    B --> D
    C --> D
    D --> G --> H --> I
    E --> H
    classDef done fill:#0d1117,stroke:#76b900,color:#c9d1d9;
    classDef now fill:#0d1117,stroke:#fbb41a,color:#c9d1d9;
    classDef next fill:#0d1117,stroke:#58a6ff,color:#c9d1d9;
    class A,B,C done
    class D,E,F now
    class G,H,I next
```

---

## 🔥 Currently Building

<table>
<tr>
<td width="50%" valign="top">

### 🌡️ GPU Heat Diffusion Simulator
`CUDA C++` · `in progress`

A 2D heat-equation solver written as CUDA kernels with **shared-memory tiling** and benchmarked against a CPU baseline for speedup and memory bandwidth. *The banner at the top of this page runs the same equation.*

**Roadmap:** multi-GPU with MPI → containerized, autoscaling GPU jobs on Kubernetes

</td>
<td width="50%" valign="top">

### ♟️ Rookery: Chess Variant Engine
`Next.js` · `React` · `TypeScript` · `capstone`

A team capstone: a platform for **creating, sharing, and playing chess variants**, with a no-code variant editor, a shared TypeScript rules engine, and real-time multiplayer.

**My role:** building the frontend UI and integrating it with the rules engine and backend services.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 MRSI Data Normalization Tool
`Python` · `PyQt6` · `openpyxl`

A desktop app that **automates processing and standardization of raw mass-spectrometer data** for McMaster's MRSI research group. It replaces manual data entry, eliminates transcription errors, and saves **several hours per dataset**. Unit-tested on edge cases and shaped by direct lab feedback.

</td>
<td width="50%" valign="top">

### 🌐 mrsi.mcmaster.ca
`PHP` · `custom CMS`

A modern rebuild of the research group's website, plus a **built-in editor** (a custom, lightweight WordPress-style CMS) that lets staff change text, images, page sections, and the site chatbot without touching code.

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<p align="center">
  <a href="https://github.com/ibrahim-parvez/Steel-Defect-Classifier"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ibrahim-parvez&repo=Steel-Defect-Classifier&theme=github_dark&hide_border=true&title_color=76b900&icon_color=76b900&bg_color=0d1117" alt="Steel Defect Classifier"/></a>
  <a href="https://github.com/ibrahim-parvez/MRSI_Data_Normalization_Tool"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ibrahim-parvez&repo=MRSI_Data_Normalization_Tool&theme=github_dark&hide_border=true&title_color=76b900&icon_color=76b900&bg_color=0d1117" alt="MRSI Data Normalization Tool"/></a>
  <a href="https://github.com/ibrahim-parvez/Double-Pendulum-Simulation"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ibrahim-parvez&repo=Double-Pendulum-Simulation&theme=github_dark&hide_border=true&title_color=76b900&icon_color=76b900&bg_color=0d1117" alt="Double Pendulum Simulation"/></a>
  <a href="https://github.com/ibrahim-parvez/EasyBudget-AI"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ibrahim-parvez&repo=EasyBudget-AI&theme=github_dark&hide_border=true&title_color=76b900&icon_color=76b900&bg_color=0d1117" alt="EasyBudget AI"/></a>
</p>

| Project | What it does | Highlights |
| :-- | :-- | :-- |
| 🏭 **Steel Defect Classifier** | CNN that classifies manufacturing defects on metal surfaces | PyTorch · 51.5M params · **91.67%** accuracy · PyQt6 GUI |
| 🌀 **Double Pendulum Simulation** | Chaotic-motion simulator with real-time visualization | C++ · Runge-Kutta · step-size convergence · **15%** less numerical error |
| 💸 **EasyBudget AI** | Shared household budgeting app on the App Store | Flutter · OCR/NLP receipt scanner |

---

## 🧰 Tech Stack

<p align="center"><b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=py,c,cpp,java,ts,js,php,html,css&theme=dark" alt="Languages"/>
</p>

<p align="center"><b>HPC & GPU</b><br/><br/>
  <img src="https://img.shields.io/badge/CUDA_C++-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA C++"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Multithreading_&_Concurrency-0d1117?style=for-the-badge&logo=linux&logoColor=76b900" alt="Concurrency"/>
</p>

<p align="center"><b>AI, Data & Frameworks</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,nextjs,react,flask,qt&theme=dark" alt="Frameworks"/>
</p>

<p align="center"><b>Cloud, DevOps & Data</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=docker,aws,azure,linux,git,postgres,mysql,vercel,firebase&theme=dark" alt="Cloud and tools"/>
</p>

<p align="center"><b>Learning next</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=kubernetes,terraform,bash&theme=dark" alt="Learning next"/>
  &nbsp;
  <img src="https://img.shields.io/badge/MPI-0d1117?style=for-the-badge&logoColor=white&labelColor=0d1117" alt="MPI"/>
  <img src="https://img.shields.io/badge/Slurm-0d1117?style=for-the-badge&logoColor=white" alt="Slurm"/>
</p>

---

## 📈 Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ibrahim-parvez&bg_color=0d1117&color=c9d1d9&line=76b900&point=fbb41a&area=true&area_color=76b900&hide_border=true&custom_title=Commits%20over%20time" alt="Contribution graph" width="100%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ibrahim-parvez&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_rank=true&title_color=76b900&icon_color=76b900&bg_color=0d1117" alt="GitHub stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ibrahim-parvez&layout=compact&theme=github_dark&hide_border=true&title_color=76b900&bg_color=0d1117" alt="Top languages" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ibrahim-parvez&theme=github-dark-blue&hide_border=true&background=0D1117&ring=76B900&fire=FBB41A&currStreakLabel=76B900" alt="Contribution streak"/>
</p>

---

<p align="center">
  <code>__global__ void build(Idea* ideas) { ship(ideas[threadIdx.x]); }</code><br/>
  <sub>Banner: a real FTCS solve of ∂u/∂t = α∇²u, rendered as an animated SVG · always open to talk about GPUs, cloud, and research software</sub>
</p>
