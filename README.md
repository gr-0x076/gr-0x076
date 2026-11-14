# Mohith GR

[Work Journal](https://github.com/gr-0x076/work-journal) · [LinkedIn](https://www.linkedin.com/in/mohith-gr-b25a6a34b/) · [Email](mailto:grmohith06@gmail.com)

Computer Science undergraduate at Scaler School of Technology and BS in Data Science & Applications student at IIT Madras. Focused on systems programming, scientific Python, and production AI engineering.

---

### Open-Source Contributions

I document the root causes, implementations, and review lessons for my upstream contributions in my [**Work Journal**](https://github.com/gr-0x076/work-journal):

- **[SciPy](https://github.com/scipy/scipy)** · [PR #26674](https://github.com/scipy/scipy/pull/26674) · **Merged**  
  Fixed an out-of-bounds filter offset in `scipy.ndimage`'s compiled C coordinate iterator macro (`NI_FILTER_GOTO`) when filtering with footprints larger than the input array along an axis, preventing memory over-reads and segmentation faults in morphological operations.

- **[SciPy](https://github.com/scipy/scipy)** · [PR #26540](https://github.com/scipy/scipy/pull/26540) · **Merged**  
  Added shape validation for the inverse covariance matrix `VI` in `scipy.spatial.distance.pdist` and `cdist` when using the Mahalanobis metric, preventing invalid matrix dimensions from triggering memory faults or silent arithmetic corruption in the compiled C kernel.

- **[statsmodels](https://github.com/statsmodels/statsmodels)** · [PR #10704](https://github.com/statsmodels/statsmodels/pull/10704) · **In Review**  
  Resolved `NaN` statistics and divide-by-zero warnings in `powerdiscrepancy` $G$-test calculations for zero observed counts by utilizing `scipy.special.xlogy` to handle mathematical limits cleanly.

---

### Selected Projects

| Project | Technologies | Summary |
| :--- | :--- | :--- |
| **[ProofGraph](https://github.com/gr-0x076/proofgraph)** | Python, Playwright, NetworkX | Citation auditor that validates LLM web citations via browser-rendered extraction, entity ambiguity detection, and discrete evidence tiers. |
| **[IncidentLens](https://github.com/gr-0x076/incidentlens)** | Python, FastAPI, Hindsight, Groq | SRE copilot using persistent agent memory to retrieve historical incident patterns and suggest mitigation steps for active outages. |
| **[Pulse Incident Engine](https://github.com/gr-0x076/pulse-incident-engine)** | Node.js, Express, React, MongoDB, Socket.IO | Real-time incident command center with deterministic state machine lifecycle transitions and SHA-256 alert deduplication. |
| **[ContextMesh](https://github.com/gr-0x076/multimodal_rag)** | Python, ChromaDB, Groq | Multimodal RAG system ingesting video, audio, PDFs, and images into a cross-modal evidence graph. |

---

### Engineering Focus

- **Languages & Systems:** Python, C, Java, JavaScript, Linux, Git
- **Data & Scientific Computing:** NumPy, SciPy, pandas, statsmodels, scikit-learn
- **Backend & AI Systems:** FastAPI, Node.js/Express, MongoDB, PostgreSQL, WebSockets, ChromaDB
