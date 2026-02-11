# 🏆 Wolfram What-If Engine

### 🥈 2nd Runner-Up @ IdeaHub 3.0 Ideathon

**Transforming qualitative "what-if" policy questions into interactive computational models.**

## 🌟 The Challenge

This project was developed for **IdeaHub 3.0**, addressing the challenge of bridging the gap between informal language and structured computation.

> **Problem Statement:** Use the Wolfram Language to explore how qualitative “what-if” questions can be transformed into explicit, interactive computational models across domains like urban systems and public policy.

## 🚀 Overview

The **Wolfram What-If Engine** is an assumption-aware simulation tool designed for urban transport planning. While traditional tools focus on static predictions, this engine focuses on **stress-testing decisions**. It reveals *when*, *where*, and *why* systems fail under specific policy interventions.

## 🧠 Core Innovation: The Qualitative-to-Computational Bridge

We move beyond "black-box" predictions by making the underlying logic transparent.

* **From Vague Questions:** "What if we increase bus frequency but people are slow to switch from cars?"
* **To Computable Models:** We map this to **Adoption Lag**, **Mode Shift**, and **Bottleneck Capacity** variables.
* **Outcome:** A dynamic simulation that identifies "threshold effects"—the exact moment a system collapses.

## 🏗️ How It Works

1. **Input:** A semi-structured "what-if" scenario.
2. **Assumption Mapping:** Identifying variables like *Crowding Tolerance* and *Strategy Rollout*.
3. **Computational Core:** A unified function `ComputeSystemState[...]` ensures consistency.
4. **Stress Simulation:** Hour-by-hour and year-by-year modeling.
5. **Visual Diagnostics:** Heatmaps and daily profiles that expose peak-hour failures.

## 🔧 Explicit Assumptions (The Parameters)

| Assumption | Policy Representation |
| --- | --- |
| **Capacity Increase** | Physical supply expansion |
| **Mode Shift** | Behavioral change and demand shift |
| **Adoption Lag** | Inertia in public uptake |
| **Strategy Preset** | Rollout timing (Linear vs. Aggressive vs. Back-loaded) |

## 📊 Key Insights Captured

* **Averages Lie:** System failures happen at the peaks, not in the daily averages.
* **Timing Matters:** Two strategies can reach the same target, but one might cause a system collapse in Year 2 due to delayed investment.
* **Threshold Effects:** Visualizing the exact point where "Unserved Load" becomes a systemic risk.

## 🛠️ Tech Stack

* **Language:** Wolfram Language (Mathematica)
* **Key Tech:** `Manipulate`, `DynamicModule`, `Associations`, `DensityPlot`.
* **Format:** Interactive Wolfram Notebook (`.nb`) compatible with Wolfram Cloud.

---

### 📂 Repository Structure

* `Project_Notebook.nb`: The primary interactive model.
* `Documentation/`: Detailed logic and ideathon presentation materials.

### 🏁 Final Thought

This project proves that computational thinking can make hidden risks visible. By making assumptions explicit, we allow policymakers to test their ideas in a safe, digital environment before a single dollar is spent on infrastructure.
