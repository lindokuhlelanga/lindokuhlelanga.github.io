# Project Upload & Repository Standard

Use this guide for every new public portfolio repository.

## General rules

1. One substantial project per repository.
2. Use lowercase kebab-case repository names, for example `network-traffic-optimization`.
3. Never commit passwords, API keys, tokens, Wi-Fi credentials, student numbers or private user data.
4. Do not upload assessment cover pages, marking rubrics or another student's identifying information.
5. Prefer source code + README + selected evidence over a large raw submission dump.
6. Every claim in a README should be something you can explain in an interview.
7. Add screenshots/diagrams only when they prove something useful.

## Recommended repository structure

```
project-name/
├── README.md
├── src/                  # Main source code
├── tests/                # Tests where applicable
├── docs/                 # Architecture, calculations, technical notes
├── screenshots/          # Selected UI or result evidence
├── data/                 # Small non-sensitive sample data only
├── scripts/              # Setup, automation or analysis scripts
├── requirements.txt      # Python dependencies, when applicable
├── .gitignore
└── LICENSE               # Add only when you intentionally choose a licence
```

Not every project needs every folder. Keep only folders that contain useful material.

---

## 1. Autonomous Drone Navigation & AI Monitoring

**Repository:** `Autonomous-Drone-Navigation` (existing)

Target structure:

```
Autonomous-Drone-Navigation/
├── README.md
├── src/
│   ├── app.py
│   ├── vision/
│   ├── ui/
│   ├── alerts/
│   └── hardware/
├── arduino/
│   └── alert_controller.ino
├── docs/
│   └── architecture.md
├── screenshots/
├── requirements.txt
└── .gitignore
```

Upload:
- Python application code
- Arduino firmware
- architecture/system diagram
- GUI screenshots
- selected detection evidence
- Telegram alert screenshot with private information removed
- dependency list

Do not upload:
- Telegram token
- Wi-Fi credentials
- personal phone/account data

---

## 2. Municipal Infrastructure Database

**Create repository:** `municipal-infrastructure-database`

```
municipal-infrastructure-database/
├── README.md
├── app/
│   ├── routes/
│   ├── models/
│   ├── services/
│   └── templates/
├── database/
│   ├── schema.sql
│   └── sample_data.sql
├── docs/
│   ├── erd.png
│   └── api.md
├── screenshots/
├── requirements.txt
├── .env.example
└── .gitignore
```

README emphasis:
Python, Flask, MySQL, SQLAlchemy, REST-style endpoints, CRUD, validation, transactions and relational design.

Never commit the real `.env` file.

---

## 3. Network Traffic Engineering & Optimisation

**Create repository:** `network-traffic-optimization`

```
network-traffic-optimization/
├── README.md
├── src/
│   ├── topology.py
│   ├── shortest_path.py
│   ├── min_cost_flow.py
│   ├── min_max_utilization.py
│   └── multi_commodity_flow.py
├── data/
│   └── topology_sample.csv
├── results/
│   └── selected_plots/
├── docs/
│   └── methodology.md
├── requirements.txt
└── .gitignore
```

README emphasis:
NetworkX, PuLP, graph theory, linear programming, GEANT2 topology, five simultaneous demands and the supported 14% maximum-utilisation result.

---

## 4. Software-Defined Networking

**Create repository:** `software-defined-networking-lab`

```
software-defined-networking-lab/
├── README.md
├── automation/
├── configs/
│   ├── ospf/
│   ├── isis/
│   └── bgp/
├── topology/
├── tests/
├── screenshots/
└── docs/
    └── failure-recovery.md
```

README emphasis:
Python-based automation/control, OSPF, IS-IS, BGP, monitoring, routing optimisation and failure testing.

---

## 5. IEEE Six-Bus Power System Analysis

**Create repository:** `ieee-6-bus-power-system-analysis`

This should be a clean technical portfolio project, not a copy of the original submitted assessment.

```
ieee-6-bus-power-system-analysis/
├── README.md
├── calculations/
│   ├── per_unit.md
│   ├── ybus.md
│   └── newton_raphson.md
├── matlab/
├── simulink/
├── digsilent/
├── protection/
│   ├── short_circuit.md
│   └── overcurrent.md
├── results/
└── docs/
    └── methodology.md
```

Technical scope:
- 150 MVA / 132 kV base
- per-unit conversion
- Ybus formation
- Newton-Raphson load flow
- MATLAB/Simulink
- DIgSILENT PowerFactory
- three-phase short-circuit analysis
- IEC 60909 settings
- overcurrent protection

Remove all identifying information belonging to the original student submission.

---

## 6. Embedded Smart-Energy Control

**Create repository:** `smart-energy-embedded-control`

```
smart-energy-embedded-control/
├── README.md
├── esp32/
├── arduino/
├── docs/
│   ├── architecture.md
│   ├── pin-map.md
│   └── control-logic.md
├── diagrams/
├── screenshots/
└── .gitignore
```

Include only code and engineering work you personally implemented and can explain.

---

## 7. FM Transmitter & Receiver

**Create repository:** `fm-transmitter-receiver`

```
fm-transmitter-receiver/
├── README.md
├── circuits/
├── calculations/
├── measurements/
├── oscilloscope/
└── docs/
    └── testing.md
```

Focus on modulation, transmitter/receiver stages, test setup, oscilloscope observations and engineering limitations.

---

## README template

Every flagship repository should answer these questions:

1. What problem was solved?
2. What did you personally build?
3. Which technologies were used?
4. How is the project structured?
5. How can someone run or reproduce it?
6. What results were measured?
7. What engineering challenges were encountered?
8. What did you learn?
9. What are the limitations or next improvements?

A recruiter should understand the project in under two minutes without opening the source code.
