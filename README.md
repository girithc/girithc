# Girith Choudhary

ML Inference Engineer · MS Software Engineering (ML), SJSU '26 · Open to full time roles from Oct 2026

## Featured

- [inference](https://github.com/girithc/inference): optimized gpu kernels to serve vision, reasoning, audio, and video llms fast and efficiently. hosted on modal.

## About

I am a machine learning systems engineer focused on LLM inference. Most of my day revolves around what it actually takes to serve models in the real world at low latency and low cost, whether that means writing custom GPU kernels, tuning KV cache behavior, or squeezing throughput out of production serving engines.

I spend a lot of time on the execution and systems layer:

Serving and inference: benchmarking and optimizing runtimes with vLLM and SGLang. I pay close attention to KV cache management, continuous batching, and chunked prefill to maximize GPU utilization while keeping TTFT and tail latency low.

Agent infrastructure: building sandboxed agent runtimes with memory for AI agents, long horizon task execution, and one click deployment to cloud VMs.

Multimodal and world models: working hands on with vision language models, speech pipelines across STT and TTS, and world models focused on state representations and spatial reasoning.

Concurrency and distributed systems: earlier experience founding a quick commerce startup where I built high concurrency Go services, Kafka event pipelines, and two tower vector retrieval systems backed by Cassandra.

Core tooling: vLLM, SGLang, Triton, PyTorch, Hugging Face, SFT, DPO, LoRA, CUDA C++, ONNX Runtime, Go, Python, C++, Docker, Kubernetes, GCP, AWS, Redis, Apache, Firecracker, E2B, Daytona style VMs, memory for AI agents.

Always down to chat with engineers, researchers, and systems builders working on GPU acceleration, inference infrastructure, or LLM serving.

## Experience

Co Founder, Otto Mart (Dec 2023 to Jan 2025)
Founded a quick commerce startup and raised a pre seed round to launch dark store operations, scaling to 1K+ users. Architected a scalable recommendation pipeline using two tower neural networks for candidate generation and wide and deep models for ranking. Engineered Go microservices for real time prediction using goroutine based worker pools, sync.Mutex, and buffered channels. Built event driven architecture with Kafka for data pipelines, Cassandra for dense vector embeddings, and PostgreSQL for transactional data. Accepted into Nvidia Inception and Microsoft for Startups.

Software Engineer Intern, AMAG Ships (May 2023 to Aug 2023)
Developed a multi task 1D CNN plus LSTM pipeline in PyTorch to detect anomalous fuel consumption and sensor drift across 10M+ telemetry points, achieving a 0.91 F1 score on simulated fault data. Profiled and accelerated inference via ONNX Runtime and NumPy vectorization within Docker containers, reducing edge evaluation latency to under 12 ms per batch.

Salesforce Developer Intern, ACA Foreside (May 2021 to Aug 2021)
Built ETL pipelines using PySpark to sync customer, invoice, and transaction data between Salesforce CRM and Microsoft Dynamics GP, processing 5M+ records with a 90% reduction in data sync errors. Developed a churn prediction model using XGBoost (AUC 0.87) on integrated CRM ERP data.

## Education

MS Software Engineering with Machine Learning, San Jose State University (expected Dec 2026)
BS Computer Science and Math, University of Alabama (May 2023)
