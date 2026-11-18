# Muatasem Hadi

**Industrial engineer using data, simulation and software to improve manufacturing.**

MEng candidate in Industrial Engineering at Telkom University, Bandung · BEng in Industrial Engineering · from Yemen.

I build the tools an improvement project actually needs: a discrete-event model to test a change before it is paid for, a control chart that says whether a process is stable, a scheduler that re-plans when a machine goes down. Every repository below runs, is tested in CI, and states plainly which numbers are simulated.

---

## Projects

| Project | What it does | Stack | Tests |
|---|---|---|---|
| **[Factory Carbon to CBAM](https://github.com/Muat01/factory-carbon-cbam)** · [live](https://factory-carbon-cbam.streamlit.app/) | Cycle times, scrap and idle power become a product carbon footprint, then an EU CBAM certificate bill, then a re-ranked improvement backlog. The headline 2.5% phase-in applies to the benchmark, not to your emissions: this plant is liable for 44% of its own in year one. A carbon border price flips two efficiency projects from cost to investment. | Pandas · Plotly · Streamlit | 123 |
| **[Production Scheduling Copilot](https://github.com/Muat01/production-scheduling-copilot)** · [live](https://muat01.github.io/production-scheduling-copilot/) | Plain-language shop-floor events → CP-SAT re-optimisation → independent feasibility checker → explanation. Matches the published optimum on 10/10 classic benchmarks; cuts weighted tardiness 77% against the best dispatching rule. | OR-Tools · Streamlit · JS | 46 |
| **[Asset Health Digital Twin](https://github.com/Muat01/asset-health-digital-twin)** | A gamma-process health index drives each machine's failure rate inside a SimPy line, so RTF / TBM / CBM / RBM maintenance policies compete on throughput and cost per good part. CBM: +12.7% throughput, −28% cost/part, −77% failures. | SimPy · Plotly · Streamlit | 24 |
| **[SPC & OEE Quality Dashboard](https://github.com/Muat01/spc-oee-quality-dashboard)** | X̄-R and I-MR charts with Western Electric rules, Cp/Cpk/Pp/Ppk, OEE loss waterfall and Pareto. Sample run: Cpk 1.34 against Ppk 1.06, OEE 70.6%. | Pandas · Plotly · Streamlit | 16 |
| **[Production Line Simulation](https://github.com/Muat01/production-line-simulation-simpy)** · [live](https://factory-line-simulator.streamlit.app) | Discrete-event model of a 4-station line with breakdowns, finite buffers and scrap, plus a what-if simulator. Predictive maintenance +9.7% throughput; one more CNC +28.7% and the bottleneck moves to Assembly. | SimPy · Streamlit | 17 |
| **[SUTM Predictive Maintenance](https://github.com/Muat01/sutm-predictive-maintenance-dashboard)** | Risk scoring and maintenance priority for 10,789 medium-voltage poles from 16,419 visual and 1,305 thermal inspection records. Academic case study with PT PLN UP3 Bandung. | Pandas · Plotly · Streamlit | 37 |
| **[Centrifugal Pump Monitoring](https://github.com/Muat01/centrifugal-pump-predictive-maintenance)** · [live](https://centrifugal-pump-predictive-maintenance.streamlit.app/) | SCADA-style condition monitoring: pressure, flow and vibration trends, a Random Forest classifier and threshold-based diagnostic checks with an asset health index. | Scikit-learn · Plotly · Streamlit | 20 |

Unless a project says otherwise, **the data is simulated** and the parameters are illustrative. Where real data was used it came from an academic case study and is not redistributed.

---

## What I work on

- **Simulation and operations research** — discrete-event models (SimPy), scheduling and optimisation (OR-Tools CP-SAT), queueing, capacity and bottleneck analysis.
- **Predictive maintenance and digital twins** — condition monitoring, health indices, hazard models, and policy comparison on cost rather than on failure counts.
- **Quality and productivity** — SPC, process capability, OEE loss analysis, work measurement.
- **Carbon and compliance** — product carbon footprints built from shop-floor data, EU CBAM exposure, and abatement curves that price an improvement backlog twice: as engineering, and again after the carbon bill it avoids.

Every project follows the same loop: **analyze → model → simulate → improve**, and reports its limitations next to its results.

---

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SimPy](https://img.shields.io/badge/SimPy-22C98A?style=flat&logoColor=white)
![OR--Tools](https://img.shields.io/badge/OR--Tools-E6B94A?style=flat&logoColor=0E1311)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

Also: FlexSim, MATLAB, R, Minitab-style SPC, and the usual lean toolkit (VSM, line balancing, time study).

---

## Currently

Finishing my master's (expected **February 2028**), building one portfolio project every few weeks, and looking for collaboration or an exchange in smart manufacturing and simulation.

**[LinkedIn](https://www.linkedin.com/in/muatasem-hadi)** · Bandung, Indonesia
