<div align="center">

# ⏱️ OptiSchedule RCPSP AI
### Resource-Constrained Project Scheduling Combinatorial Optimizer

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=EF4444&center=true&vCenter=true&width=750&lines=OptiSchedule+RCPSP+AI;Resource-Constrained+Project+Scheduling;AWS+Batch+High-Performance+Computing;Genetic+Algorithms+%2B+Neural+Control" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Batch_HPC_Cluster-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Optimization-Genetic_%2B_Neural_Heuristics-0052CC?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Benchmark-PSPLIB_Standard-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Preserved-Branch_Ex-gray?style=for-the-badge&logo=git" />
</p>

<img src="https://skillicons.dev/icons?i=python,pytorch,aws,docker&theme=dark" alt="Stack" />

</div>

---

### 📊 Scheduling Optimizer HUD

```yaml
Dataset        : PSPLIB J120 Benchmark (120 Activities, 4 Renewable Resources)
Algorithm      : Neural-Controlled Genetic Algorithm (NC-GA)
Population     : 200 Individuals | 100 Generations
Critical Path  : 142 Days (Lower Bound)
Achieved Makespan : 148 Days (Optimality Gap: 4.2%)
Execution Time : 14.8 seconds on AWS Batch compute environment
```

---

## 🏛️ Optimization Bento Grid

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🧬 Neural-Guided Metaheuristics</h3>
      <p>Combines genetic algorithm crossover/mutation operators with neural value functions to dynamically select serial schedule generation scheme (SSGS) rules.</p>
      <b>Features:</b> Precedence feasibility preservation • Makespan minimization
    </td>
    <td width="50%" valign="top">
      <h3>⚡ AWS Batch Cluster Compute</h3>
      <p>Dispatches heavy combinatorial evaluation jobs across dynamically scaled EC2 Spot instances, reducing computation cost by up to 80%.</p>
      <b>Features:</b> Parallel instance scaling • S3 scenario loading
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 Interactive Gantt Visualizer</h3>
      <p>Interactive Plotly/Streamlit Gantt chart visualization highlighting resource over-allocation bottlenecks, task floats, and critical chain paths.</p>
      <b>Features:</b> Resource usage curves • Task dependency hover
    </td>
    <td width="50%" valign="top">
      <h3>📜 Academic Research Rigor</h3>
      <p>Accompanied by full research papers, literature surveys, and baseline evaluations against classic heuristic dispatch rules (LFT, LST, MINSLK).</p>
      <b>Features:</b> Full mathematical formulations • PSPLIB verification
    </td>
  </tr>
</table>

---

## ⚡ Quickstart

```bash
git clone https://github.com/prak05/OptiSchedule-RCPSP-AI.git
cd OptiSchedule-RCPSP-AI
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

---

<div align="center">
<sub>Preserved Baseline: <a href="https://github.com/prak05/OptiSchedule-RCPSP-AI/tree/Ex">branch Ex</a> • Engineered for Scalable Production Clouds</sub>
</div>
