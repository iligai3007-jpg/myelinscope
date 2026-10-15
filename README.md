# MyelinScope: Computational Neuroscience Research Platform

MyelinScope is an independent computational neuroscience software library designed to model axon electrophysiology, characterize custom synthetic myelin sheath materials, and simulate targeted delivery pathways. 

**Develoment Status:** Alpha / Prototype Framework V1.0  
**Target Audience:** Computational biology researchers, bioengineering students, and biomaterial designers.  
**Disclaimer:** *MyelinScope is a research and educational simulation platform. It is not an FDA-approved clinical diagnostic system.*

## Core Modules
- **01: Axon Electrical Simulator** – Models cable theory parameters (membrane resistance, capacitance, and length constants).
- **02: Synthetic Myelin Designer** – Profiles multi-layered dielectric synthetic polymers.
- **03: Self-Wrapping Feasibility Model** – Evaluates Helfrich surface free-energy minimization thresholds against micro-fiber cylinders.
- **04: Delivery Feasibility Model** – Simulates multi-compartment pharmacokinetic curves tracking blood-brain barrier (BBB) transit.
- **05: Myelin Imaging + Statistics** – Quantifies morphological metrics, including axonal g-ratio distributions.

## Quick Start
```bash
pip install -r requirements.txt
python myelinscope_engine.py
```