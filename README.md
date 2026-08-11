<div align="center">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
  <img src="https://github.com/user-attachments/assets/4e814ecf-fccc-4878-b888-21cc5a69ac3c" width="20%">
</div>

# About me
- @HungryNeko
- **Backend Engineering + AI Engineering** (CV, speech, RL, multimodal)
- **Current focus**: production AI pipelines (ONNX inference, Dockerized services, async cloud workflows, agent tools)
- **Interests**: IoT backend, speech processing, AI agents, and research-to-production engineering
- **More technical notes**: [Blog Posts](https://fujisaki.top/)

# Tech Stack
| Area | Stack |
| --- | --- |
| **Languages** | Python, C/C++, Java, C#, SQL |
| **AI/ML** | PyTorch, TensorFlow, Hugging Face Transformers, LangGraph, scikit-learn, OpenCV, YOLOv8, ONNX, ONNX Runtime |
| **Speech & Multimodal** | Whisper, MossFormer2, SpeechBrain, WeSpeaker, cross-lingual speaker verification, code-switch analysis |
| **Backend & Cloud** | Node.js, Flask, REST APIs, JWT, MySQL, SQLite, Docker, Linux, MQTT, AWS (EC2/S3/SQS/Lambda/DynamoDB/IAM/Secrets Manager), Azure |
| **Frontend** | React, Angular, HTML |
| **Engineering** | Git, GitHub Actions, CI/CD, async job pipelines, PyQt, QT, TCP/IP, COLMAP, 3D Gaussian Splatting |

# Selected Projects
- **AI-Powered Rental Management Agent Platform**
  - **Tech**: Flask, SQLite, JWT, LangGraph, SQL tool, Python tool, chart tool, PDF tool, contract RAG.
  - **Features**: natural-language data entry, record update/query, charting, PDF handling, and retrieval-augmented contract search.
  - [Github](https://github.com/HungryNeko/rent)

- **AMECxSV: Metadata-Driven Calibration for Cross-Lingual Speaker Verification**
  - **Tech**: frozen speech encoders, metadata-aware score calibration, language/duration features, lightweight MLP.
  - **Focus**: cross-lingual speaker verification, multilingual trials, confidence-based abstention.

- **GBC: Gaussian-Based Colorization and Super-Resolution for 3D Reconstruction**
  - **Tech**: optical-flow super-resolution, temporal colorization, FFmpeg preprocessing, COLMAP + 3D Gaussian splatting.
  - **Publication**: ACM SIGGRAPH VRCAI 2024.
  - [Blog](https://fujisaki.top/pages/paper/gbc-gaussian-based-colorization-and-super-resolution-for-3d-reconstruction/post) [Paper](https://dl.acm.org/doi/10.1145/3703619.3706039) [Demo](https://elucidator.cn/gbc-demo/) [Github](https://github.com/ffftuanxxx/GBCA)

- **BMS^3: Bayesian Modeling Based SwinUNet Segmentation on Self-distillation Architecture**
  - **Tech**: Bayesian modeling, SwinUNet backbone, self-distillation, cross-domain segmentation setup.
  - **Publication**: ICONIP 2025.
  - [Blog](https://fujisaki.top/pages/paper/bms3-bayesian-modeling-based-swinunet-segmentation-on-self-distillation-architecture/post) [Paper](https://link.springer.com/chapter/10.1007/978-981-95-4445-5_3) [Reference List](https://elucidator.cn/bmsss_ref/)

- **Safety-driven Path Selection Using Reinforcement Learning in Autonomous Driving**
  - **Tech**: Q-learning, dynamic confidence update, noisy-source filtering, OpenStreetMap-based routing context.
  - **Publication**: RSAE 2025.
  - [Blog](https://fujisaki.top/pages/paper/safety-driven-path-selection-using-reinforcement-learning-in-autonomous-driving/post.html)

- **Multilingual Speech Separation + Code-switch Correction Pipeline (Ongoing)**
  - **Tech**: MossFormer2, Whisper, PyTorch, SpeechBrain/WeSpeaker, custom TDNN/SincNet variants.
  - **Experiments**: short-window cross-lingual speaker verification benchmark across ECAPA, x-vector, WavLM, Resemblyzer, and custom models, with ablation + speed/accuracy comparison.

- **AI Cloud Album (AWS)**
  - **Tech**: Flask, JWT, S3, SQS, Lambda, DynamoDB, IAM, Secrets Manager, status-driven async workflow (`uploaded -> processing -> complete/failed`).
  - **AI Deployment**: YOLOv8 inference exported to ONNX and packaged with Docker for reproducible cloud inference.
  - [Blog](https://fujisaki.top/pages/tech/aws-cloud-album-project/post.html)

- **R2 Gateway**
  - **Tech**: Flask, Docker, Cloudflare R2, S3-compatible APIs, Flask-Limiter.
  - **Features**: Dockerized R2 gateway with token-based access control, public/private bucket policy, traffic and operation-quota guardrails, and health/usage endpoints.
  - [Blog](https://fujisaki.top/pages/tech/r2-gateway-cost-controlled-s3-compatible-object-storage-gateway/post.html)

- **SAR Data Pipeline with YOLOv8**
  - **Tech**: YOLOv8, OpenCV preprocessing, augmentation pipeline, format conversion, classification/detection/OBB training.
  - **Metrics**: 35% effective data expansion, 12% accuracy improvement over baseline.


> Note: Some projects are in private repositories (course/research or confidentiality reasons).
