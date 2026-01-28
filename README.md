# ⭐ Universal What-If Engine  
### Assumption-Aware Simulation for Urban Transport Policy

![Wolfram](https://img.shields.io/badge/Wolfram-Language-red?logo=wolfram&logoColor=white)

**Turn vague policy questions into computational experiments.**  
Reveal *when*, *where*, and *why* urban transport systems fail.

*Built for planners, policymakers, researchers, and systems thinkers.*

## 🚦 Why This Project Exists

Most urban transport tools answer the wrong question.

They ask:
- How many passengers will we have?
- What is the average congestion?

But real systems fail because:
- Demand spikes at specific hours
- Capacity is constrained by hidden bottlenecks
- Human behavior changes slowly
- Infrastructure rollout is mistimed

**The Universal What-If Engine is designed to expose those failures before they happen.**

## 🧠 What This Is

A reusable, assumption-aware simulation engine that models public transport systems under policy interventions — hour-by-hour and year-by-year.

Current domains:
- 🚆 Urban train expansion  
- 🚌 Public bus fleet expansion  

Same engine. Different constraints.

## 🎯 What This Is Not

- Not a demand forecast  
- Not a real-time dashboard  
- Not a black-box AI predictor  

This tool is about **decision stress-testing**, not prediction.

## 🏗️ How It Works (High Level)

Policy Question  
↓  
Explicit Assumptions  
↓  
Computational Core  
↓  
System Stress Simulation  
↓  
Visual Diagnostics  

Every output comes from a single function: ComputeSystemState[year, hour, …]

This guarantees **consistency, traceability, and debuggability**.

## 🔧 Assumptions (Made Explicit)

Each slider corresponds to a real policy assumption:

| Assumption | What It Represents |
|-----------|--------------------|
| Capacity Increase | Supply expansion |
| Mode Shift | Human behavior change |
| Crowding Tolerance | Safety threshold |
| Adoption Lag | Behavioral inertia |
| Bottleneck Capacity | Physical constraints |
| Strategy | Rollout timing |
| Weather | External stress |

If an assumption changes, the outcome changes.  
Nothing is hidden.

## 🧭 Strategy Presets (Critical Insight)

Strategy controls **when capacity is delivered**, not how much.

- **Linear** → Even rollout  
- **Aggressive (Front-Loaded)** → Early investment  
- **Back-Loaded** → Delayed deployment  

Two strategies can reach the same final capacity —  
only one avoids early-year collapse.

## 📊 What the Visuals Tell You

### Simulation View  
Live snapshot of demand, capacity, unserved load, and system health.

### Daily Profile  
Shows why averages lie — failures occur at peak hours.

### Strategy Curve  
Separates policy intent from execution timing.

### Heatmap (Stress Analysis)  
Hour × Year grid revealing future failure windows.

### Logic View  
Maps vague questions to explicit equations.

## 🔍 Why This Is Different

Most planning tools optimize metrics.

This engine exposes:
- Hidden constraints  
- Early failure points  
- Trade-offs between speed and safety  
- The cost of delayed investment  

It answers **“When does this break?”**, not just **“Does this improve?”**

## 🏙️ Where This Can Be Used

- Urban transport planning  
- Infrastructure budgeting  
- Policy comparison and defense  
- Climate stress testing  
- Systems-thinking education  
- Hackathons and research demos  

## 📓 Notebook

The full **interactive Wolfram Notebook (`.nb`)** used to build and demonstrate this engine is included **below in the repository**.

It contains:
- The complete computational core  
- All visualizations and UI logic  
- Live `Manipulate`-based exploration  

Open the notebook in **Wolfram Mathematica** or **Wolfram Cloud** to interact with the model.

## 🛠️ Tech Stack

- **Language:** Wolfram Language (Mathematica)  
- **Core Constructs:** `Manipulate`, `DynamicModule`, `Associations`, `DensityPlot`  
- **Deployment:** Wolfram Cloud compatible  

## 📌 Design Principles

- Assumptions over optimism  
- Bottlenecks over averages  
- Timing over final targets  
- Transparency over black boxes  

## 🏁 Final Thought

This model does not predict the future.  
It reveals how our assumptions shape it — and where systems fail first.

⭐ If you believe systems should be tested before they are built, consider starring this repository.
