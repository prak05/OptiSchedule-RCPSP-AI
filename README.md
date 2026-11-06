# OptiSchedule — AI-Enhanced Metaheuristic Project Scheduling (RCPSP)

[![AWS Batch](https://img.shields.io/badge/AWS-Batch%20%7C%20ECS-FF9900?logo=amazon-aws&logoColor=white)](#aws-cloud-architecture)
[![Algorithms](https://img.shields.io/badge/Algorithms-Genetic%20%7C%20Neural%20Control-0052CC)](#metaheuristics-engine)
[![Branch Status](https://img.shields.io/badge/Preservation-Ex%20Branch-22C55E)](#branch-architecture)
[![License: MIT](https://img.shields.io/badge/License-MIT-gray.svg)](LICENSE)

> Resource-Constrained Project Scheduling Problem (RCPSP) optimization engine combining genetic algorithms, constraint satisfaction, and neural hyper-heuristic control.

---

## 1. Executive Brief
Large-scale infrastructure and software projects suffer from multi-million dollar delays caused by resource contention. **OptiSchedule** solves the NP-hard Resource-Constrained Project Scheduling Problem using deep reinforcement and neural-guided metaheuristics to minimize total project makespan under strict precedence constraints.

* **Preservation**: Academic paper research and original code preserved on [`Ex`](https://github.com/prak05/OptiSchedule-RCPSP-AI/tree/Ex).
* **Architecture**: Containerized AWS Batch computing jobs with S3 scenario vaults and interactive Gantt scheduling visualizer.

---

## 2. AWS Cloud Architecture

```mermaid
flowchart TD
    Planner["Project Planner / EPC Firm"] --> APIGW["Amazon API Gateway"]
    APIGW --> S3Scenarios["Amazon S3 (Project Precedence & Resource Data)"]
    S3Scenarios --> BatchTrigger["AWS Lambda (Job Dispatcher)"]
    BatchTrigger --> AWSBatch["AWS Batch (High-Throughput Genetic Algorithm Cluster)"]
    AWSBatch --> Dynamo["Amazon DynamoDB (Schedule Optimizations & Makespan Metrics)"]
    Dynamo --> Streamlit["Interactive Gantt & Schedule Visualizer (ECS Fargate)"]
```

---

## 3. Branch Architecture
* [`main`](https://github.com/prak05/OptiSchedule-RCPSP-AI/tree/main): High-performance scheduling engine with AWS Batch configuration.
* [`Ex`](https://github.com/prak05/OptiSchedule-RCPSP-AI/tree/Ex): Preserved academic prototype and paper artifacts.

<!-- antigravity-certified -->
