# 📘 Game Dev Math & Physics Roadmap

A curated, application-focused guide to mastering the **math and physics** that power modern game engines.  
Designed for self-learners who can dedicate **~1 hour per day**.

---

## ✅ Bare Minimum Path (Essentials Only)

This sequence gets you building believable gameplay systems and real-time simulations **with the least calendar time**.

| # | Book / Resource | Est. Time | Why It Matters |
|---|-----------------|-----------|----------------|
| 1 | *Precalculus* — Stewart | 3 months | Algebra & trig foundations for vectors, angles, and parametric curves. |
| 2 | *3D Math Primer for Graphics & Game Development* | 2–3 months | Vectors, matrices, quaternions, projections – the lingua franca of every engine. |
| 3 | *Calculus: Early Transcendentals* — Stewart (Core chapters 2–14) | 4 months | Derivatives & integrals that underpin motion, forces, and animation easing. |
| 4 | **Physics Kick-off:** *Physics for Game Developers* — Dunn & Parberry | 1–2 months | Hands-on intro to kinematics, forces, torques, and simple integrators. |
| 5 | **Collisions Deep-Dive:** *Real-Time Collision Detection* — Ericson | 1.5–2 months | How engines know when and where objects touch – SAT, GJK, BVHs. |
| 6 | *Practical Statistics for Data Scientists* | 1–2 months | Randomness, AI probability, analytics, procedural generation. |
| 7 | *Game Programming Algorithms & Techniques* | 2 months | Path-finding, AI steering, finite-state gameplay – math in action. |
| 8 | **Capstone:** *Game Physics Engine Development* — Eberly | 3–4 months | Build a rigid-body engine: constraint solver, joints, collision response. |

**🕒 Total Time:** ~19 months @ 1 h / day  
(*Items 4 & 5 can overlap to keep total near 18 months.*)

**By the end you’ll:**

- Integrate rigid-body physics, collisions, and constraints in UE / Unity.  
- Build AI and procedural features that rely on solid math.  
- Read engine source code (e.g., Chaos, PhysX) without getting lost in the symbols.

---

## 📚 Supplemental Reading (Grow as Needed)

These titles unlock specialised domains once the essentials feel comfortable.

| # | Book | Est. Time | When & What to Pair With |
|---|------|-----------|---------------------------|
| 1 | *Numerical Recipes in C++* | 3–4 months | After *Calculus* + *Physics Kick-off*. Optimisers, ODE solvers, noise. |
| 2 | *Practical Optimization* | 2–3 months | After *Game Algorithms*. AI tuning, IK, constraint correction. |
| 3 | *Real-Time Rendering* | 2–3 months | Alongside or after *3D Math Primer*. Shaders, GPU maths. |
| 4 | *Game Engine Architecture* | 2–3 months | After *Capstone Physics Engine*. Systems-level context. |
| 5 | *Discrete Mathematics with Applications* | 2–3 months | After *Statistics*. Graphs, sets, logic for networking & rule systems. |
| 6 | *Differential Equations & Linear Algebra* | 3–4 months | After *Capstone Physics Engine*. Cloth, fluids, procedural motion. |
| 7 | *Fluid Simulation for Computer Graphics* — Bridson | 2 months | After Diff-Eq. Splashy VFX, Houdini smoke & fire. |
| 8 | Papers: **Position-Based Dynamics** & **Advanced Character Physics** | 1 month ea. | When implementing soft-body, rag-dolls, or character controllers. |
| 9 | *The Scientist & Engineer’s Guide to DSP* | 1–2 months | Procedural audio, signal-driven FX after *Game Algorithms*. |
|10 | *Concrete Mathematics* | 3–4 months | After *Discrete Math*. Deep combinatorics for novel gameplay systems. |

---

## 🚀 Micro‑Projects to Cement Concepts

1. **Projectile Sandbox** – Semi‑implicit Euler vs. Verlet; plot energy drift.  
2. **Pinball Table** – Convex SAT/GJK collision playground.  
3. **Rag‑Doll Demo** – Chain of joints with PD controllers, test stability.  
4. **Destruction Testbed** – Houdini fracture → Chaos destruction import.  
5. **AI Steering Lab** – Combine pathfinding with physics‑based obstacle avoidance.

*(Each project ≤ 2 weeks @ 1 h/day)*

---

## ⚡ Iteration Turbochargers (Unreal‑Specific)

| Topic | Why It Super‑charges Iteration | Quick Resources |
|-------|--------------------------------|-----------------|
| **Blueprint ⇄ C++ Bridging** | Hot‑reload logic in Blueprints while heavy math stays native C++; exposes tweakable variables to designers | UE Docs “Exposing Variables to BP” • GDC ’23 “BP Nativization” |
| **Python & Editor Scripting** | Batch‑rename assets, auto‑import FBX, mass‑edit data tables in seconds | UE Python API docs • “Blutility” tutorials |
| **Live Coding / Hot Reload** | Recompile single files without restarting the editor; keeps flow state intact | UE Live Coding guide |
| **Gameplay Ability System (GAS)** | Data‑driven combat / power framework—cut implementation time for new abilities | UE GAS Docs • Tom Looman’s GAS series |
| **Data Assets & Reflection** | Tweak JSON‑like `UDataAsset` values in editor, avoid hard‑coding constants | Epic “Data Driven Design” streams |
| **Automation & Testing** | Functional / unit tests catch regressions overnight; Commandlet scripts snapshot perf | UE Automation Spec reference |
| **Profiling with Unreal Insights** | Frame‑step, CPU/GPU, network traces—pinpoint slow loops fast | Epic Learning “Using Insights” |
| **Source‑Control Workflow** | Git‑LFS / Perforce locks large binaries; branch strategy avoids merge hell | Epic “Perforce Best Practices” |
| **Build, Cook, CI/CD** | One‑click package + auto‑smoke tests ensures you iterate on gameplay, not build fixes | UnrealBuildTool docs • Jenkins/XGE examples |
| **Modular Plugins & Marketplace** | Encapsulate features, enable hot‑swap; reuse across prototypes/projects | UE Plugin anatomy docs |

*📈 Add ~2 months (1 h/day) to cover these hands‑on, ideally interleaved with ongoing projects.*

---

## 🎯 How to Use This Roadmap

1. **Follow the bare‑minimum list** unless a current project demands a supplemental topic.  
2. **Overlap compatible books** (e.g., Items 4 & 5) to shorten calendar time.  
3. **Code while you read** – a 200‑line demo beats 20 pages of passive reading.  

---

## 📌 Suggested Study Cadence

- **Daily:** 1 focused hour – 40 min reading, 20 min coding/notes.  
- **Weekly:** Sunday 30 min retro – log blockers, plan next pages & code checkpoints.  
- **Monthly:** Mini‑project or blog post to consolidate what you learned.  

> *Stay playful. The fastest way to absorb math & physics is to watch it break
> your game in hilarious ways—then fix it.* 🎮
