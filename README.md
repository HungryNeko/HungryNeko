<div align="center">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
</div>

# About me
- @HungryNeko
- **Backend Engineering + AI Engineering** (CV, speech, RL, multimodal)
- **Current focus**: production AI pipelines (ONNX inference, Dockerized services, async cloud workflows)
- **Interests**: IoT backend, speech processing, and research-to-production engineering
- **More technical notes**: [blog posts](https://fujisaki.top/category/%E6%8A%80%E6%9C%AF-tech/)

# Tech Stack
| Area | Stack |
| --- | --- |
| **Languages** | Python, C/C++, Java, SQL |
| **AI/ML** | PyTorch, TensorFlow, scikit-learn, OpenCV, YOLOv8, ONNX, ONNX Runtime |
| **Speech & Multimodal** | Frameworks: Whisper, MossFormer2, SpeechBrain, WeSpeaker<br>Focus: short-window cross-lingual speaker verification, code-switch analysis |
| **Backend & Cloud** | Flask, REST APIs, JWT, MySQL, Docker, Linux, MQTT, AWS (EC2/S3/SQS/Lambda/DynamoDB/IAM/Secrets Manager), Dockerized ONNX inference services |
| **Engineering** | Git, GitHub Actions, CI/CD, async job pipelines, PyQt, TCP/IP |

# Selected Projects
- **Multilingual Speech Separation + Code-switch Correction Pipeline (Ongoing)**
  - **Tech**: MossFormer2, Whisper, PyTorch, SpeechBrain/WeSpeaker, custom TDNN/SincNet variants.
  - **Experiments**: short-window (~1s) cross-lingual speaker verification benchmark across ECAPA, x-vector, WavLM, Resemblyzer, and custom models, with ablation + speed/accuracy comparison.

- **AI Cloud Album (AWS)**
  - **Tech**: Flask, JWT, S3, SQS, Lambda, DynamoDB, IAM, Secrets Manager, status-driven async workflow (`uploaded -> processing -> complete/failed`).
  - **AI Deployment**: YOLOv8 inference exported to ONNX and packaged with Docker for reproducible cloud inference.

- **IoT Debugging & Testing System (Intern)**
  - **Tech**: Python, PyQt, MQTT, queue-based multithreading, protocol encryption, JSON-driven test framework.
  - **Metrics**: 40% operation-time reduction, up to 80% less adaptation code, <20ms latency, 40% lower CPU usage.

- **GBC: Gaussian-Based Colorization and Super-Resolution for 3D Reconstruction**
  - **Tech**: optical-flow super-resolution, temporal colorization, FFmpeg preprocessing, COLMAP + 3D Gaussian splatting.
  - **Publication**: ACM SIGGRAPH VRCAI 2024.

- **BMS^3: Bayesian Modeling Based SwinUNet Segmentation on Self-distillation Architecture**
  - **Tech**: Bayesian modeling, SwinUNet backbone, self-distillation, cross-domain segmentation setup.
  - **Publication**: ICONIP 2025.

- **Safety-driven Path Selection Using Reinforcement Learning in Autonomous Driving**
  - **Tech**: Q-learning, dynamic confidence update, noisy-source filtering, OpenStreetMap-based routing context.
  - **Publication**: RSAE 2025.

- **SAR Data Pipeline with YOLOv8**
  - **Tech**: YOLOv8, OpenCV preprocessing, augmentation pipeline, format conversion, classification/detection/OBB training.
  - **Metrics**: 35% effective data expansion, 12% accuracy improvement over baseline.

<!--# What I have uploaded
- Experiment projects for papers
- Some class projects
- Personal projects
- Some web links and files for personal use
- Notice: Some repositories are not published (for personal use or for certain confidentiality reasons)-->

# Project Links
- GBC: [Archived Repo](https://github.com/ffftuanxxx/GBC) | [Paper](https://dl.acm.org/doi/10.1145/3703619.3706039)
- Safety-driven Path Selection: [Abstract](https://fujisaki.top/2025/04/15/safety-driven-path-selection-using-reinforcement-learning-in-autonomous-driving/)
- BMS^3: [Abstract](https://fujisaki.top/2024/11/02/bms3-bayesian-modeling-based-swinunet-segmentation-on-self-distillation-architecture/)
- Image Compression Study: [Report](https://github.com/HungryNeko/EE510project/blob/main/EE510_Report.pdf) | [Repository](https://github.com/HungryNeko/EE510project/)

> Note: Some projects are in private repositories (course/research or confidentiality reasons).
