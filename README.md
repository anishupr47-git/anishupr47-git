<div align="center">

# Anish Upreti
### Systems Engineer • Machine Learning Infrastructure • Open Source Author

[![PyPI - tiered-semantic-cache](https://img.shields.io/badge/PyPI-tiered--semantic--cache-000000?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/tiered-semantic-cache/)
[![PyPI - towergb](https://img.shields.io/badge/PyPI-towergb-000000?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/towergb/)
[![GitHub](https://img.shields.io/badge/GitHub-anishupr47--git-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anishupr47-git)
[![Email](https://img.shields.io/badge/Email-anish.upr.47%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anish.upr.47@gmail.com)

</div>

***

### Engineering Track Record

* Winner (1st Place), National AI Hackathon 2026 for DRISTI_OS: Engineered a low-latency, dual-stack backend coordinating agentic tool-calling, asynchronous speech-to-text streams via Deepgram, and frontier LLM reasoning pipelines using Python, FastAPI, and TypeScript[cite: 5].
* Author of tiered-semantic-cache on PyPI: Architected an offline two-tiered semantic caching daemon featuring an in-memory L1 cache with O(1) LRU eviction, zero-copy memory-mapped (mmap) L2 disk persistence, and a custom AsyncIO TCP daemon implementing the Redis RESP wire protocol, reducing redundant LLM query latency from 3s to sub-milliseconds[cite: 5].
* Author of TowerGB on PyPI: Built a Scikit-Learn compatible gradient-boosted ensemble framework with automated missing data preprocessing and Platt/temperature calibration, validated across an automated 69-test CI/CD suite[cite: 5].
* Scaled Production Data Systems: Refactored PostgreSQL indexing and ORM query architectures across FastAPI and Django microservices, cutting response latencies by 30% to 35% with zero downtime[cite: 5].

***

### Architecture and Core Technologies

#### Runtimes and Languages
<p>
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-000000?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=white" />
</p>

#### AI Systems and Modeling
<p>
  <img src="https://img.shields.io/badge/PyTorch-000000?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-000000?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-000000?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-000000?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-000000?style=for-the-badge&logo=google&logoColor=white" />
</p>

#### Backend, Storage and Cloud
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-000000?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-000000?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-000000?style=for-the-badge&logo=celery&logoColor=white" />
</p>

***

### Systems Architecture & Production Benchmarks

| System / Engine | Core Architecture & Protocol | Key Benchmarks & Production Metrics | Runtime & Stack | Status |
| :--- | :--- | :--- | :--- | :--- |
| [**tiered-semantic-cache**](https://github.com/anishupr47-git/tiered-semantic-cache) | Offline two-tiered semantic caching engine with custom AsyncIO TCP daemon implementing Redis RESP wire protocol, O(1) LRU eviction, and zero-copy `mmap` disk persistence[cite: 5]. | **< 1ms response latency** (reduced from ~3.0s LLM round-trips); zero-copy memory-mapped disk I/O; linear memory scaling under concurrent reads[cite: 5]. | Python, AsyncIO, Redis/RESP, mmap[cite: 5] | [![PyPI](https://img.shields.io/pypi/v/tiered-semantic-cache?color=000000&label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/tiered-semantic-cache/)[cite: 5] |
| [**TowerGB**](https://github.com/anishupr47-git/TowerGB) | Scikit-Learn compatible gradient-boosted ensemble framework with automated missing-feature imputation and Platt/temperature probability calibration[cite: 5]. | **100% CI pass rate** across automated 69-test suite; deterministic probability calibration; 100+ active downloads on PyPI[cite: 5]. | Python, Scikit-Learn, NumPy, CI/CD[cite: 5] | [![PyPI](https://img.shields.io/pypi/v/towergb?color=000000&label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/towergb/)[cite: 5] |
| [**DRISTI_OS**](https://github.com/anishupr47-git) | Dual-stack voice-to-agent engine coordinating asynchronous streaming speech-to-text, agentic tool execution, and frontier reasoning models[cite: 5]. | **1st Place Champion** (National AI Hackathon 2026); real-time bidirectional audio streaming via Deepgram with sub-second agent tool dispatch[cite: 5]. | FastAPI, TypeScript, Deepgram STT, LLM APIs[cite: 5] | Production Hackathon Build[cite: 5] |
| **Enterprise Data Microservices** | High-throughput distributed backend services, asynchronous Celery workers, and PostgreSQL query execution refactoring[cite: 5]. | **30%–35% API latency reduction** via B-tree indexing and ORM query optimization; zero production downtime across multi-tenant deployments[cite: 5]. | FastAPI, Django REST, PostgreSQL, Redis, Docker[cite: 5] | Commercial Production[cite: 5] |

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anishupr47-git&layout=compact&theme=dark&hide_border=true&bg_color=000000&title_color=FFFFFF&text_color=999999" width="55%" />

</div>
