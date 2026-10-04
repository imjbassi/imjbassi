# 👋 Hi, I'm Jaiveer Bassi

**AI Robot Operator** at Physical Intelligence<br>
**MS in Software Engineering** · **BS in Computer Science**

I build systems across **robotics**, **machine learning**, **AI reliability**, and **full-stack software**. My recent work focuses on robot-fault diagnostics, demonstration-data quality, reproducible ML evaluation, and scientific benchmark auditing.

---

## Research & Publications

- **[Curation Metrics Are a Post-Training Decision: Auditing Trajectory Smoothness for Adapting Robot Foundation Models](https://github.com/imjbassi/smoothness-audit)**: **Accepted as a poster at the [NeurIPS 2026 RoboPAD workshop](https://openreview.net/forum?id=wj9Kj3hsJs).** Builds on the base preprint *Smoothness Ranks Skill, Not Success: An Audit of Published Trajectory-Smoothness Curation Metrics Under Episode-Length Controls*; the [CoRL WEBP](https://openreview.net/forum?id=8HHUxS9GcK) and [CoRL Oops, I Erred](https://openreview.net/forum?id=7C6WROjCKQ) versions remain under review.

- **[Not All Bad Demonstrations Are Equally Bad: Quantifying How Demonstration Failure Modes Degrade Closed-Loop Policy Performance](https://github.com/imjbassi/demo-quality-robustness)**: Controlled study of 660 policy fits across five failure modes, two policy families, ten seeds, and transition-matched controls. Under review at the CoRL 2026 Learning from Corrections and Interventions workshop ([OpenReview](https://openreview.net/forum?id=DBSdaBnibW)).

- **[What Can Three Seeds and Fifty Rollouts Resolve? A Preregistered Audit of Operator and Seed Variance on robomimic Multi-Human Benchmarks](https://github.com/imjbassi/operator-variance-audit)**: Preregistered audit of 138 BC-RNN runs splitting robomimic Multi-Human benchmark variance into seed, demonstration, operator, and rollout noise. At 50 rollouts, ten seeds were statistically indistinguishable on every task; re-evaluating 46 Square checkpoints at 500 rollouts made the seed effect detectable and erased an apparent operator-proficiency pattern. Under review at the CoRL 2026 SimBench2Real workshop ([OpenReview](https://openreview.net/forum?id=jmZMj6QkeI)), with a [preprint](https://www.researchgate.net/publication/415199249_What_Can_Three_Seeds_and_Fifty_Rollouts_Resolve_A_Preregistered_Audit_of_Operator_and_Seed_Variance_on_robomimic_Multi-Human_Benchmarks) and [Zenodo archive](https://doi.org/10.5281/zenodo.23109850).

- **[One Byte, One Rank Reversal: Auditing HumanEval Pipeline Sensitivity for Base Code Models](https://github.com/imjbassi/local-deployment-of-transformer-based-code-assistants)**: A pinned five-model reproduction on an RTX 4070 found StarCoder2-3B scoring 3/164 instead of its published 31.7%, reversing a published ranking. Removing one trailing newline from the evaluation prompt raised it to 49/164 and restored the order. Technical report v1.9 with a [versioned Zenodo archive](https://doi.org/10.5281/zenodo.22926448). **[PDF](https://github.com/imjbassi/local-deployment-of-transformer-based-code-assistants/blob/main/paper/output/pdf/Do_Published_HumanEval_Rankings_Survive_Local_Deployment.pdf)**

- **[When Does INT8 Actually Accelerate Host-CPU Inference? A Reproducible Audit of MobileNetV2 Conversion and Packaging](https://github.com/imjbassi/efficient-ai-edge-deployment)**: Shows that INT8 latency depends on backend delegation and quantization granularity, alongside paired accuracy and packaging controls. Released as [v1.2.0 on Zenodo](https://doi.org/10.5281/zenodo.22758817), not yet submitted for peer review.

- **[Conditioning and Directionality in Adversarial Transfer on CIFAR-10](https://github.com/imjbassi/transferability-of-adversarial-attacks)**: Denominator-aware full-test study across three architectures and three training seeds. Under review at Transactions on Machine Learning Research ([OpenReview](https://openreview.net/forum?id=0wQCiGLqZx)), with an [archived reproducibility release](https://doi.org/10.5281/zenodo.22737839).

- **[Complete Patient-Level Leakage Among Traceable Images in a Widely Used Brain Tumor MRI Benchmark](https://github.com/imjbassi/brain-tumor-mri-classification)**: Finds complete patient overlap among traceable tumor test images plus substantial duplicate contamination, and releases patient-disjoint folds. Available as a preprint and [Zenodo artifact](https://doi.org/10.5281/zenodo.22755070), not yet submitted to a journal.

- **[Sampling Budget Biases Apparent Metastable-State Counts in Molecular Simulation](https://github.com/imjbassi/state-count-sampling-bias)**: Controlled synthetic landscapes and two independent alanine-dipeptide trajectories show how sampling budget can inflate apparent state counts. Under review at JCTC (submitted September 15, 2026), with a [ChemRxiv preprint](https://chemrxiv.org/doc/3ca81cab-c111-4416-99f8-0b2654e38da7) and a [versioned Zenodo dataset](https://doi.org/10.5281/zenodo.22754433).
---

## Technical Skills

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Assembly](https://img.shields.io/badge/x86--64_Assembly-6E4C13?style=flat-square)

### AI, ML & Scientific Computing

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

### Robotics, Infrastructure & Web

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![SocketCAN](https://img.shields.io/badge/SocketCAN-4B4B4B?style=flat-square)
![UR RTDE](https://img.shields.io/badge/UR_RTDE-00A0DC?style=flat-square)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

## Selected Projects

- **[π0 on a Budget](https://github.com/imjbassi/pi0-on-a-budget)** — Fine-tuning π0-FAST on a consumer RTX 4070 using synchronized demonstrations from a custom four-degree-of-freedom teleoperation arm, followed by open-loop and closed-loop evaluation.

- **[Demonstration Quality Robustness](https://github.com/imjbassi/demo-quality-robustness)** — Controlled simulation study of 660 policy fits measuring how specific demonstration failure modes degrade closed-loop policy performance, and how poorly open-loop evaluation tracks that damage. [Paper (PDF)](https://github.com/imjbassi/demo-quality-robustness/blob/master/paper.pdf).

- **[UR5e RTDE Fault-Injection Harness](https://github.com/imjbassi/ur5e-rtde-harness)** — Drives a simulated UR5e over RTDE, the same interface used by production UR5e cells, logs synchronized joint telemetry, and deliberately induces connection faults to characterize whether the client fails with a clean exception, a hang, or a native crash.

- **[openpi Language-Steerability Demo](https://github.com/imjbassi/openpi-steerability-demo)** — Runs the public π0.5 LIBERO checkpoint in a single simulated scene with different language instructions and scores success with the simulator's own goal checks. Trained and paraphrased prompts succeed 10/10, while novel object recombinations drop as low as 1/10.

- **[Grasp Annotation Dataset Pipeline](https://github.com/imjbassi/grasp-annotation-dataset)** — Data-ops pipeline that samples public robot-arm video into frames, provisions a Labelbox project with a grasp-focused ontology, and exports completed labels as COCO JSON. Each frame can carry a `grasp_event` bounding box, an `object_contact` keypoint, and a `failure_mode` label (drop, miss, collision, timeout, or success).

- **[CAN Bus Fault Injector](https://github.com/imjbassi/can-bus-fault-injector)** — Three-node Arduino/MCP2515 CAN bus with SocketCAN monitoring and a documented catalog of physical and protocol-level faults. [Article on Medium](https://imjbassi.medium.com/simulating-real-robot-failures-a3c62fbfc62d).

- **[GELLO-Style Leader–Follower Arm](https://github.com/imjbassi/gello-lite)** — Approximately $30 potentiometer-based teleoperation rig using direct joint-space control without inverse kinematics. [Article on Medium](https://imjbassi.medium.com/a-30-teleoperation-rig-rebuilding-the-core-idea-behind-robot-demonstration-data-69df3d1431f3).

- **[Scribbot](https://github.com/imjbassi/scribbot)** — A low-cost, mostly 3D-printed desktop robot arm that draws on a 3 × 3 inch sticky note: an MG90S base on a 2:1 printed gear, MG996R shoulder and elbow, an MG90S wrist, and a gravity pen holder, driven by an Arduino Nano and PCA9685 servo driver, with OpenSCAD sources, printable STLs, and stage-by-stage build guides.

- **[Chess-RL Engine](https://github.com/imjbassi/chess-reinforcement-learning)** — AlphaZero-inspired engine that learns only through self-play: a C++ bitboard move generator exposed through pybind11, a PyTorch policy/value network on an 18-channel board encoding, and a PyGame interface showing move probabilities in real time.

- **[Neural Net Mapper](https://github.com/imjbassi/neural-net-mapper)** — Trains an MLP on a synthetic shapes dataset and renders an animated map of its inner workings: neuron activations, weight signs and magnitudes, dropout, predictions, and live loss/accuracy curves.

- **[MedStract](https://medstract.net)** — Flask web app that retrieves peer-reviewed abstracts from PubMed and turns them into summaries calibrated to four reading levels, from the general public to the domain expert, with question answering over the results, publication-trend charts, and citation exports (APA, MLA, Chicago, Vancouver, BibTeX, RIS).

- **[Castline Studio](https://castline.studio)** — Production e-commerce order system with client-side STL analysis, Etsy and shipping integrations, and automated email.

---

## Experience

### Undergraduate Research Fellow — *Stanford University*
*Stanford, CA · September 2026–Present*

### AI Robot Operator — *Physical Intelligence*
*San Francisco, CA · May 2026–Present*

- Generate high-quality demonstrations for general-purpose robotics foundation models by teleoperating robotic arms through manipulation, sorting, and assembly tasks.
- Evaluate model behavior against quality benchmarks, identify edge cases and failure modes, and annotate task data for model development.
- Diagnose recurring hardware–software faults across distributed robotics systems by tracing failures through service logs and documenting root causes for engineering teams.

### LLM Response Evaluator — *Handshake AI*
*Remote · April 2026–June 2026*

- Evaluated LLM-generated code and technical responses across AI/ML and software-engineering domains, scoring correctness, instruction following, and writing quality.

### Software Developer — *Kaiser Permanente*
*Berkeley, CA · October 2023–June 2024*

- Developed a React, Express, REST, and SQL application for uploading, processing, and reviewing clinical-laboratory instrument data.
- Built validated data pipelines that consolidated more than 50 instrument fields into an automated upload workflow.
- Investigated data-recording defects, documented failure patterns, and improved pipeline reliability.

---

## Certifications

- **[Accelerated Computing in Modern CUDA C++](https://learn.nvidia.com/certificates?id=eaNdEd3OSJ-b3kGRexaGkg)** *(September 2026)*
- **[HackerRank Software Engineer Certificate](https://www.hackerrank.com/certificates/fa189046801d)** *(March 2026)*
- **[Cisco Network Support and Security](https://www.credly.com/badges/9d0c624f-c2ea-4dde-9edf-f7ab096b3003/public_url)** *(September 2025)*
- **[IBM Artificial Intelligence Fundamentals](https://www.credly.com/badges/9499939c-56c2-4760-9ccd-b8399fd97d31/public_url)** *(August 2025)*
- **[Stanford Fundamentals of AI and Machine Learning in Healthcare](https://imjbassi.github.io/credentials/stanford-ai-healthcare-transcript.pdf)** *(June 2025)*
- **[Google Foundations of Project Management](https://www.coursera.org/account/accomplishments/verify/DQ3EEK89IWI6)** *(September 2024)*
- **[Google IT Support Professional Certificate](https://www.coursera.org/account/accomplishments/professional-cert/6KPKTL6896VT)** *(May 2021)*

---

## Education

- **MS, Software Engineering** — Grand Canyon University *(May 2024–October 2025)*
- **BS, Computer Science** — University of Silicon Valley *(May 2021–August 2023)*

---

## Connect

<a href="https://www.linkedin.com/in/jaiveer-bassi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/imjbassi"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://imjbassi.github.io"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
<a href="https://www.researchgate.net/profile/Jaiveer-Bassi"><img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate"></a>

---

*Open to full-time opportunities in robotics software, AI/ML engineering, full-stack development, and AI reliability.*
