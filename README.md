<div align="center">

<img src="https://fujisaki.top/media/web/image.png" width="110" alt="HungryNeko">

# HungryNeko

**AI / Software Engineer, taking ideas from research papers to shipped software.**

ML / AI engineering

[![Blog](https://img.shields.io/badge/Blog-fujisaki.top-24292e?style=for-the-badge)](https://fujisaki.top/)

| 5,000+ | 3 |
| :---: | :---: |
| Flathub downloads of AkiZip in its first month | published papers (3D vision, medical imaging, RL) |

</div>

# What I do

My work sits where research meets engineering: models that get exported, containerised, put behind an API and used by someone other than me.

- **Shipped software**: a native Linux desktop app with thousands of users.
- **Applied ML research**: speaker verification, 3D reconstruction, medical segmentation and reinforcement learning, with published results.
- **AI systems**: LLM agents with tool use, ONNX inference in Docker, asynchronous AWS pipelines.

# Selected Projects

## Shipped software

| Project | What it is | Built with | Links |
| --- | --- | --- | --- |
| **AkiZip** ![stars](https://img.shields.io/github/stars/AkiZip/AkiZip?style=social)<br>*Co-developer* | Visual 7-Zip archive manager for Linux. Smart compression recommendations, password protection, cancellable background jobs, 8 UI languages. 5,000+ downloads on Flathub in its first month. | Python, GTK 4, libadwaita, 7-Zip, Flatpak, meson | [Repo](https://github.com/AkiZip/AkiZip) · [Site](https://akizip.top) · [Blog](https://blog.akizip.top) |

## Research

| Project | What it is | Built with | Links |
| --- | --- | --- | --- |
| **AMECxSV**<br>*arXiv · co-first author · under review* | Metadata-aware calibration for cross-lingual speaker verification. Fuses scores from frozen speech encoders with language and duration cues through a lightweight MLP, with confidence-based abstention. Full-coverage EER 2.15% → 1.85%. | Frozen speech encoders, score fusion, lightweight MLP | [arXiv](https://arxiv.org/html/2607.16532v1) |
| **SPARC**<br>*Computer Speech & Language (in preparation)* | A portable calibration plug-in for speaker verification. Corrects the LLR scores of frozen encoders with anchored residuals and score fusion, no retraining. | ECAPA-TDNN, CAM++, WavLM, LLR calibration, score fusion | [Page](https://hungryneko.github.io/SPARC) · [Code](https://github.com/HungryNeko/SPARC) |
| **GBC**<br>*ACM SIGGRAPH VRCAI 2024 · co-first author* | Colour 3D scenes from monochrome video: super-resolution and temporal colorization feeding a 3D reconstruction pipeline. Parallel workflow cut processing time by 37%. | Optical flow, FFmpeg, COLMAP, 3D Gaussian Splatting | [Paper](https://dl.acm.org/doi/10.1145/3703619.3706039) · [Demo](https://elucidator.cn/gbc-demo/) · [Code](https://github.com/HungryNeko/GBC) · [Blog](https://fujisaki.top/pages/paper/gbc-gaussian-based-colorization-and-super-resolution-for-3d-reconstruction/post) |
| **Safety-driven Path Selection**<br>*RSAE 2025 · first author* | Trust estimation for route choice in autonomous driving, with a dynamic confidence update and noisy-source filtering. +10% average precision over the reference model. | Q-learning, OpenStreetMap | [Paper](https://ieeexplore.ieee.org/document/11488131) · [Blog](https://fujisaki.top/pages/paper/safety-driven-path-selection-using-reinforcement-learning-in-autonomous-driving/post.html) |
| **BMS³**<br>*ICONIP 2025 · team member* | Bayesian segmentation with self-distillation for cross-domain medical images. | SwinUNet, Bayesian modeling, self-distillation | [Paper](https://link.springer.com/chapter/10.1007/978-981-95-4445-5_3) · [Blog](https://fujisaki.top/pages/paper/bms3-bayesian-modeling-based-swinunet-segmentation-on-self-distillation-architecture/post) · [References](https://elucidator.cn/bmsss_ref/) |

## AI systems & backend

| Project | What it is | Built with | Links |
| --- | --- | --- | --- |
| **Rental Management Agent Platform**<br>*Ongoing* | A property-management backend you can talk to. A decoupled MCP agent handles natural-language data entry, queries, charts, PDF/image handling and RAG over contracts. | Flask, SQLite, JWT, LangGraph, MCP, vector RAG | [Agent](https://github.com/HungryNeko/AI_Agent) |
| **AI Cloud Album**<br>*AWS · course project* | Photo album with asynchronous AI tagging. Uploads move through a status-driven pipeline (`uploaded → processing → complete/failed`); YOLOv8 is exported to ONNX and served from a Docker image. | Flask, S3, SQS, Lambda, DynamoDB, IAM, ONNX, Docker | [Repo](https://github.com/HungryNeko/AI-Cloud-Album-AWS-) · [Write-up](https://fujisaki.top/pages/tech/aws-cloud-album-project/post.html) |
| **R2 Gateway**<br>*Cloudflare R2* | Cost-controlled front door for object storage: token-based access, public/private bucket policy, traffic and operation quotas, health and usage endpoints. | Flask, Docker, S3-compatible APIs, Flask-Limiter | [Repo](https://github.com/HungryNeko/r2-gateway) · [Write-up](https://fujisaki.top/pages/tech/r2-gateway-cost-controlled-s3-compatible-object-storage-gateway/post.html) |

> Some projects live in private repositories (course, research or confidentiality reasons). Happy to walk through them in conversation.
