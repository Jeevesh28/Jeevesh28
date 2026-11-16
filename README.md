# Hey there, I'm Jeevesh! 👋

MS Computer Science at UW-Madison (May 2027). I like working on the layer underneath a product: the backend services, data pipelines and ML systems that need to be fast, correct and easy to trust. Most recently a Data Science Intern at Cloudflare. Before graduate school, 2+ years at Oracle building backend services and data infrastructure.

**Looking for new grad and early career Software Engineering and ML/AI Engineering roles, starting June 2027.**

## Selected work
 
**Budget Beam: Adaptive Search Effort for Vector Search** · *C++, Python, LightGBM, HNSW*
 
Adaptive search effort for HNSW, since most queries finish early while a small tail needs far more work. Each query keeps widening only while a learned model predicts the recall gain is worth the extra work, and a resumable C++ kernel never recomputes a distance. On 1M MS MARCO passages it runs 1.43 to 1.67x faster than fixed-ef HNSW at matched recall.
 
**[Adaptive GPU Traversal for Irregular Graphs](https://github.com/Ayuushii/adaptive-gpu-bfs)** · *CUDA, C++, OpenMP, Nsight*
 
An adaptive CUDA BFS engine for irregular graphs, where a few hub vertices leave most GPU threads idle. It switches between push and pull per frontier and routes vertices to threads, warps or blocks by degree, with each mechanism ablated separately. On power-law graphs it runs 11 to 66x faster than a conventional CUDA BFS.
 
**[Open source: RSEM](https://github.com/deweylab/RSEM)** (merged upstream) · *C++17, CMake, Python, CI*
 
A C++17 modernization of RSEM, a widely cited RNA-Seq quantification tool that had no automated tests. I removed its Boost dependency with a drop-in RNG, added a regression suite across four aligners with cross-platform CI, and ported its Perl drivers to Python 3. Every result still reproduces bit-for-bit, merged upstream in [#233](https://github.com/deweylab/RSEM/pull/233) · [#234](https://github.com/deweylab/RSEM/pull/234) · [#235](https://github.com/deweylab/RSEM/pull/235)
 
**[CoT-Faithfulness](https://github.com/Jeevesh28/CoT-Faithfulness)** · *Python, PyTorch, LLM APIs*
 
A causal test of whether chain-of-thought reasoning actually drives a model's answer. Reasoning traces are perturbed four ways and re-injected via assistant prefilling, with attention analysis on Llama to back the behavioral result. Across Llama 3.1 8B, Gemma 3 12B and Claude Opus 4.6, faithfulness falls as capability rises: 0.49, 0.30, 0.09.
 
**[Intelligent-Bistro](https://github.com/Jeevesh28/Intelligent-Bistro)** · *TypeScript, React Native, Expo, Express, Zod*
 
A conversational ordering app, where the hard part is trusting an LLM with a live cart. Claude turns natural-language orders into Zod-validated tool calls, and UI taps and AI calls share one cart-mutation path with pricing computed server-side. The model's view of the cart never drifts from the user's, backed by 45 tests.

## Tech

- **Languages & Core:** C · C++ · Python · Java · JavaScript · TypeScript · SQL · HTML/CSS · MATLAB
- **Backend & Distributed Systems:** Spring Boot · Microservices · REST APIs · Node.js · Express.js · gRPC · Kafka · Redis
- **ML & Modeling:** PyTorch · TensorFlow · Keras · Scikit-learn · Hugging Face · XGBoost · LightGBM · Pandas · NumPy · MLflow
- **LLM & Agents:** RAG · MCP · AI Agents · Vector Search (Faiss) · LangChain · Fine-Tuning (LoRA) · Claude Code · Cursor · Codex
- **Systems & HPC:** CUDA · OpenMP · Multithreading · CMake
- **Data & Storage:** Spark · Cassandra · HDFS · BigQuery · Elasticsearch · Oracle · MongoDB
- **Cloud & DevOps:** AWS · GCP · OCI · Docker · Kubernetes · Jenkins (CI/CD) · Git · Linux

## Background
 
**Experience**
- **Cloudflare**, Data Science Intern · Jun 2026 - Aug 2026
- **UW-Madison Data Science Institute**, Open Source Developer · Feb 2026 - Jun 2026
- **Oracle**, Applications Developer · Jun 2023 - Aug 2025

**Education**
- **UW-Madison**, MS Computer Science · 2025 - May 2027
- **IIT Kharagpur**, B.Tech (Hons.) Mechanical Engineering, Minor in Mathematics & Computing · 2019 - 2023

**Publication**
- [DARSI: A deep auto-regressive time series inference architecture for forecasting of aerodynamic parameters](https://www.sciencedirect.com/science/article/pii/S1877750324001947), *Journal of Computational Science* (Elsevier), 2024

## Connect
 
- Email: [jmahajan2@wisc.edu](mailto:jmahajan2@wisc.edu)
- LinkedIn: [linkedin.com/in/Jeevesh28](https://www.linkedin.com/in/Jeevesh28)
