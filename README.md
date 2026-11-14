# Hi, I'm Mohith GR 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohith-gr-b25a6a34b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/gr-0x076)
[![Work Journal](https://img.shields.io/badge/Work%20Journal-gray?style=flat&logo=github)](https://github.com/gr-0x076/work-journal)
[![Email](https://img.shields.io/badge/Email-grmohith06%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:grmohith06@gmail.com)

**Computer Science Undergraduate @ Scaler School of Technology | BS in Data Science & Applications @ IIT Madras**

I am focused on software engineering, AI/ML systems, backend development, and open-source scientific Python.

I learn by building projects, investigating real-world bugs, contributing to existing codebases, and documenting the engineering decisions behind my work.

---

### 🔬 Open-Source Contributions

I document the problem, investigation, implementation, and lessons learned from each contribution in my [**Work Journal**](https://github.com/gr-0x076/work-journal).

- **[SciPy](https://github.com/scipy/scipy)** · [PR #26674](https://github.com/scipy/scipy/pull/26674) · **Merged**  
  Fixed an out-of-bounds filter offset in `scipy.ndimage`'s compiled C coordinate iterator macro (`NI_FILTER_GOTO`) when filtering with footprints larger than the input array along an axis, preventing memory over-reads and segmentation faults in morphological operations.

- **[SciPy](https://github.com/scipy/scipy)** · [PR #26540](https://github.com/scipy/scipy/pull/26540) · **Merged**  
  Added shape validation for the inverse covariance matrix `VI` in `scipy.spatial.distance.pdist` and `cdist` when using the Mahalanobis metric. The validation prevents incompatible matrix shapes from reaching the lower-level distance kernel, where they could cause buffer over-reads or silent arithmetic errors. Added regression tests for both functions.

- **[statsmodels](https://github.com/statsmodels/statsmodels)** · [PR #10704](https://github.com/statsmodels/statsmodels/pull/10704) · **In Review**  
  Fixed handling of zero observed counts in `powerdiscrepancy` $G$-test calculations, using `scipy.special.xlogy` to handle mathematical limits cleanly and avoid `NaN` statistics and divide-by-zero warnings.

---

### 🚀 Selected Projects

| Project | Technologies | What it explores |
| :--- | :--- | :--- |
| **[ProofGraph](https://github.com/gr-0x076/proofgraph)** | Python, NetworkX, LLMs | Evidence-backed claim verification: atomic claim extraction, source retrieval, evidence assessment, and graph-based relationships between claims and sources. |
| **[IncidentLens](https://github.com/gr-0x076/incidentlens)** | Python, FastAPI, Hindsight, Groq | An incident-investigation assistant that uses persistent memory to retrieve relevant historical incidents and support troubleshooting. |
| **[Pulse Incident Engine](https://github.com/gr-0x076/pulse-incident-engine)** | React, Node.js, Socket.IO, TanStack Query, MongoDB | Real-time incident management application with explicit lifecycle transitions, hash-based deduplication, and live updates. |
| **[ContextMesh](https://github.com/gr-0x076/multimodal_rag)** | Python, ChromaDB, Groq, Whisper | A multimodal RAG system for retrieving information from PDFs, images, audio, and video, with source and timestamp grounding. |

---

### 🛠️ Technologies I've Worked With

- **Languages:** Python, Java, JavaScript, SQL
- **Backend & Application Development:** FastAPI, Node.js, Express, REST APIs, WebSockets
- **Data & AI/ML:** NumPy, pandas, SciPy, scikit-learn, PyTorch, ChromaDB, NetworkX
- **Databases & Tools:** PostgreSQL, MongoDB, Git, Linux, Docker, Postman

---

### 📚 How I Learn

- Work on real codebases and investigate bugs instead of relying only on tutorials.
- Practice implementing mathematical and algorithmic concepts from scratch.
- Participate in open-source contributions and learn through community code reviews.
- Document technical decisions, debugging processes, and lessons in my [**Work Journal**](https://github.com/gr-0x076/work-journal).
