### Hi there, I'm Aayush Motiani 👋

I'm a Computer Science graduate from **UC San Diego**. I enjoy learning and building systems, from writing low-level Rust plugins for game engines to building custom information retrieval systems from scratch.

---

### 🛠️ Tech Stack & Skills
* **Languages:** Python, Rust, C++, C#, Java
* **Systems & Native:** Memory optimization, performance profiling, ECS (Entity Component System) architecture, 3D vector math
* **AI & Data:** Gemini API, OpenAI API, RAG pipelines, HNSW vector search, BM25
* **Tools & Engines:** Unity, Bevy (Rust), PostgreSQL, FastAPI, Git, Docker, Visual Studio Code

---

### 💼 Experience

**Software Engineer Intern | VinVR** *(Jan 2026 – Jun 2026)*
* Contributed production features to a large-scale Rust codebase on the Bevy engine, worked inside a complex ECS (Entity Component System) architecture under strict memory-ownership constraints.
* Built a Rust plugin for the Bevy engine that streams 3D environment assets from the Cesium API via asynchronous requests, maintaining strict memory-safety constraints throughout.
* Programmed an adaptive Level of Detail (LOD) system using geodetic-to-ECEF coordinate math to load and render only the 3D meshes within a user's immediate radius, cutting unnecessary asset loads.
* Developed an Autodesk Revit extension that embeds material metadata into GLTF exports, automating the texturing pipeline so assets auto-texture on import into the engine.

**Software Engineer Intern | The Net VR** *(Jun 2025 – Sep 2025)*
* Designed and built an AI companion system integrating Gemini and OpenAI APIs into a real-time UI, including real-time Speech-to-Text and Text-to-Speech.
* Refactored a C# player controller into a modular state machine, adding coyote time and jump buffering to improve gameplay feel.
* Diagnosed and resolved 15+ critical bugs in a live, shipped Unity build including Cinemachine camera jitter, Rigidbody physics conflicts, and UI/collision issues.
* Wrote technical documentation and PR guidelines that sped up code review and onboarding for new teammates.

**Software Engineer Intern | Origami Air Co.** *(Jan 2024 – Mar 2024)*
* Built a physics-based vehicle/flight controller in Unity supporting both VR (6DoF) and desktop keyboard input.
* Designed an asymmetric drag model to separate gravity and drag math in Unity's PhysX engine, fixing floaty physics and an inertia bug caused by ForceMode.Force.
* Built a custom 3D vector math stabilizer that auto-corrected vehicle orientation in real time, cutting motion sickness by ~60%.
* Built an internal debug tool exposing physics parameters as runtime UI sliders so designers and pilots could tune vehicle handling live with zero code changes.

---

### 🚀 Featured Projects

* **[Hybrid RAG Search Engine](https://github.com/amotiani/RAG)** *(Python, NumPy, PostgreSQL, FastAPI, Gemini API)*
  * Built a custom Retrieval-Augmented Generation (RAG) search engine, programming HNSW vector indexing and BM25 sparse retrieval algorithms entirely from scratch to bypass reliance on managed vector databases.
  * Engineered a multi-stage retrieval pipeline that merges dense and sparse semantic scores using Reciprocal Rank Fusion (RRF), layered with a cross-encoder for reranking.

* **[Simulife: Emergent AI NPC Societies](https://github.com/amotiani/Simulife-Emergent-AI-NPC-Societies)** *(C#, Unity, Gemini API)*
  * Built a chess AI using minimax search with alpha-beta pruning and custom board-evaluation heuristics, tested against baseline agents for legal, strong move selection.

* **[Chess-Playing AI Engine](https://github.com/amotiani/Chess-AI-CSE150B)** *(Python)*
  * Built a multi-agent simulation of AI-driven NPCs on the Gemini API, with real-time turn-taking logic and custom handling to hide model response latency from the player.

---

### 📫 Let's Connect
* **Email:** amotiani1234@gmail.com
* **LinkedIn:** [linkedin.com/in/aayushmotiani](http://linkedin.com/in/aayushmotiani)
* **Portfolio / GitHub:** [github.com/amotiani](https://github.com/amotiani)
