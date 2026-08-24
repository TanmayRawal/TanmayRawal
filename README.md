<p align="center">
  <a href="https://tanmayrawal.github.io/">
    <img src="https://raw.githubusercontent.com/TanmayRawal/tanmayrawal.github.io/main/public/og.png" width="100%" alt="Tanmay Rawal — ML and AI Research Engineer" />
  </a>
</p>

<h3 align="center">Research engineer building intelligent systems for real-world constraints.</h3>

<p align="center">
  Production ML · Trustworthy Medical AI · Edge Inference · Agentic Systems
</p>

<p align="center">
  <a href="https://tanmayrawal.github.io/"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://tanmayrawal.github.io/Tanmay-Rawal-Resume.pdf"><strong>Résumé</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/tanmay-rawal-10b0a7278/"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:23DEC511@lnmiit.ac.in"><strong>Email</strong></a>
</p>

---

## Profile

I work where machine learning meets constrained hardware, human trust, and production reality. My work spans national-scale power forecasting, interpretable medical imaging, quantized CNN inference on FPGA, and evidence-grounded multi-agent systems.

I am pursuing an integrated **B.Tech–M.Tech in Electronics and Communication Engineering at LNMIIT, Jaipur**, where I am ranked **#1 in the Integrated Dual Degree program**. I have worked as an **ML Intern at NTPC Ltd.** and a **Research Intern at LUSIP, LNMIIT**.

My strongest work tends to connect three layers:

- **Model behavior** — accuracy, robustness, explanation quality, and failure analysis.
- **System design** — data pipelines, retrieval, orchestration, evaluation, and reproducibility.
- **Deployment constraints** — latency, quantization, accelerator compatibility, and deterministic execution.

## Research signal

| **0.92% MAPE** | **13.9× speedup** | **98.8% accuracy** | **98.4 FPS** | **2 papers** |
|:---:|:---:|:---:|:---:|:---:|
| Power-demand forecasting | FPGA vs. CPU inference | Brain-tumor MRI ensemble | Alzheimer’s staging | Published + accepted |

## Selected systems

| Work | Research question | Evidence |
|---|---|---|
| [**India-wide power-demand forecasting**](https://github.com/TanmayRawal/India_Power_Demand_forcaster) | Can multi-horizon demand forecasting remain accurate and fast enough for operational power-trading decisions? | **0.92% MAPE** · 340K+ records · four horizons · 288-block forecast in under 2.5 s |
| [**Interpretable brain-tumor classification**](https://github.com/TanmayRawal/Brain-Tumor-MRI-Classification-Using-Ensemble-CNN-XAI-and-Hardware-Accelerated-Edge-Deployment) | Can an accurate MRI ensemble provide complementary explanations without losing deployability? | **98.8% accuracy** · 7,421 scans · Grad-CAM + SHAP + LIME · INT8 within 0.3% of FP32 |
| [**Real-time Alzheimer’s staging on FPGA**](https://github.com/TanmayRawal/Alzheimer-Classification-Using-Hardware-Accelerated-CNN-on-PYNQ-ZU-FPGA-with-Arm-Processor) | Can clinical CNN inference run deterministically on constrained hardware without CPU fallback? | **98.4 FPS** · 10.15 ms latency · **13.9×** speedup · 423 DPU operations |
| [**ResolveAI**](https://github.com/TanmayRawal/ResolveAI) | Can a multi-agent support workflow remain grounded, cited, and policy-compliant? | **100% compliance** · 100% citation coverage · four agents · MCP interface |
| [**AES-128 hardware accelerator**](https://github.com/TanmayRawal/AES128-hardware-accelerator) | Can standards-compliant encryption be integrated as a verified, timing-clean SoC peripheral? | 12 cycles per block · AXI4-Lite · 0.236 W · byte-for-byte software verification |

<p align="right"><a href="https://tanmayrawal.github.io/#work">Explore the complete case studies →</a></p>

## Publications

**Published · IHCI 2025**<br />
[**INSIGHT-BRAIN: Interpretable Neural Systems Using Grad-CAM, SHAP, and LIME in Human-Centered Brain Tumor Imaging**](https://books.google.co.in/books?id=QFPlEQAAQBAJ&pg=PA301)

An explainability-centered framework for making ensemble MRI decisions more transparent to human stakeholders through complementary local and global explanations.

**Accepted · IEEE TENCON 2026**<br />
**DPU-Accelerated Alzheimer’s Disease Staging from Brain MRI Using Quantized ResNet50 on PYNQ-ZU** — accepted for presentation.

This work connects clinical computer vision with deployable edge inference through INT8 quantization, DPU compilation, and accelerator-native execution.

## Research experience

<table>
<tr>
<td width="50%" valign="top">
<p><strong>2026 · MACHINE LEARNING INTERN</strong></p>
<h3>NTPC Ltd. · IT Department</h3>
<p>Built and operationalized a four-horizon electricity-demand forecasting pipeline for power-trading decisions.</p>
<ul>
<li>Combined grid telemetry, live weather, autoregressive lags, and calendar effects.</li>
<li>Engineered 21 predictive features over more than 340K records.</li>
<li>Optimized the SQL and NumPy pipeline by 12×.</li>
<li>Delivered coverage for all Indian states and union territories.</li>
</ul>
</td>
<td width="50%" valign="top">
<p><strong>2025 · RESEARCH INTERN</strong></p>
<h3>LUSIP · LNMIIT</h3>
<p>Developed an interpretable MRI ensemble and took it from training to real-time FPGA deployment.</p>
<ul>
<li>Combined EfficientNetB0, InceptionV3, and Xception.</li>
<li>Integrated Grad-CAM, LIME, and SHAP explanations.</li>
<li>Quantized and compiled the ensemble with Vitis AI.</li>
<li>Retained accuracy within 0.3% of the FP32 pipeline.</li>
</ul>
</td>
</tr>
</table>

## Technical toolkit

| Area | Technologies |
|---|---|
| **Languages & compute** | Python · C++ · SQL · CUDA · VHDL |
| **Machine learning & AI** | PyTorch · TensorFlow · Scikit-learn · XGBoost · Deep Learning · Computer Vision · Time-Series Forecasting · XAI · Feature Engineering |
| **GenAI & LLM systems** | RAG · LangChain · CrewAI · FAISS · Hugging Face · Sentence Transformers · Multi-Agent Systems · MCP |
| **Edge & deployment** | Docker · Linux · Git · ONNX · TensorRT · Vitis AI · PYNQ-ZU · FPGA Acceleration · INT8 Quantization |
| **Data & applications** | NumPy · Pandas · OpenCV · Streamlit · Django · FastMCP · APScheduler · Gemini · Open-Meteo |

## Research approach

1. **Start with a measurable baseline.** Define the accuracy, latency, reliability, or compliance target before adding complexity.
2. **Treat explanation as an engineering requirement.** Use interpretation and validation methods that reveal where a model is right, wrong, or uncertain.
3. **Design for the target environment.** Quantization, tool constraints, memory, latency, and hardware compatibility belong in the research loop—not after it.
4. **Report evidence, not only architecture.** Compare against baselines and communicate the result with reproducible metrics.

## Recognition

- **Rank #1** — Integrated Dual Degree Program, LNMIIT Jaipur.
- **54th among 1,200+ global teams** — Nokia FPGA Hackathon, Top 100 Finalist.
- **Published at IHCI 2025** and **accepted at IEEE TENCON 2026**.
- **Integrated B.Tech–M.Tech, ECE** — The LNM Institute of Information Technology, Jaipur (2023–2028).

---

<p align="center">
  <strong>Can it be measured? Can it be explained? Can it run where it matters?</strong>
</p>

<p align="center">
  <a href="https://tanmayrawal.github.io/">tanmayrawal.github.io</a>
</p>
