---
layout: default
title: Sarayu Sivakumar Dhaya
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#070b18;
  --panel:#111a2f;
  --border:rgba(255,255,255,.08);
  --text:#e6edf7;
  --muted:#b3c0d4;
  --accent:#22c55e;
  --accent2:#38bdf8;
}

*{ box-sizing:border-box; }

html, body{
  margin:0;
  padding:0;
  font-family:'Inter',sans-serif;
  color:var(--text);
  background:
    radial-gradient(1200px 600px at 20% 10%, rgba(56,189,248,.15), transparent 60%),
    radial-gradient(1000px 600px at 80% 20%, rgba(34,197,94,.12), transparent 60%),
    linear-gradient(180deg,#060913 0%,#070b18 100%);
}

.main-content,
.container,
.container-lg,
.markdown-body,
article{
  max-width:none !important;
  padding:0 !important;
  margin:0 !important;
}

footer{ display:none !important; }

.wrapper{
  width:min(1150px, calc(100vw - 80px));
  margin:0 auto;
  padding:100px 0;
}

.section{ margin:120px 0; }

h1{
  font-size:58px;
  font-weight:800;
  margin:0;
}

h2{
  font-size:40px;
  font-weight:700;
  margin:0 0 25px 0;
}

.accent{ color:var(--accent); }

.subtitle{
  font-size:22px;
  margin-top:25px;
  color:var(--muted);
  line-height:1.8;
}

.rule{
  width:90px;
  height:3px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  border-radius:999px;
  margin:30px 0 40px 0;
}

.card{
  background:linear-gradient(180deg,rgba(17,26,47,.95),rgba(15,23,42,.9));
  border:1px solid var(--border);
  border-radius:18px;
  padding:50px;
  margin-bottom:50px;
  box-shadow:0 20px 60px rgba(0,0,0,.35);
}

.card h3{
  font-size:26px;
  margin-bottom:10px;
}

.meta{
  font-size:15px;
  color:rgba(255,255,255,.6);
  margin-bottom:18px;
}

ul{
  padding-left:25px;
}

li{
  margin-bottom:15px;
  font-size:18px;
  color:var(--muted);
  line-height:1.8;
}

.metrics{
  display:flex;
  gap:30px;
  flex-wrap:wrap;
  margin-top:25px;
}

.metric{
  background:rgba(255,255,255,.03);
  border:1px solid var(--border);
  padding:18px 24px;
  border-radius:12px;
  font-size:16px;
}

.button{
  display:inline-block;
  padding:14px 26px;
  border-radius:12px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  color:#000;
  font-weight:600;
  text-decoration:none;
  margin-top:25px;
}

.contact{
  text-align:center;
  margin-top:120px;
}

.contact p{
  color:var(--muted);
  font-size:18px;
}
</style>

<div class="wrapper">

<!-- HERO -->
<div class="section">
  <h1>Sarayu <span class="accent">Sivakumar Dhaya</span></h1>
  <div class="subtitle">
    AI Engineer specializing in Multimodal RAG Systems, Agentic LLM Architectures, and Production-Grade Deep Learning Systems.
  </div>
</div>

<!-- SUMMARY -->
<div class="section">
  <h2 class="accent">About</h2>
  <div class="rule"></div>

  <p class="subtitle">
  Master’s graduate in Artificial Intelligence with 5+ years of backend and distributed systems experience. I design and build applied AI systems that combine deep learning, multimodal retrieval, and LLM-based reasoning with measurable evaluation and deployment focus.
  </p>
</div>

<!-- FEATURED PROJECT -->
<div class="section">
  <h2 class="accent">Featured Project — Agentic Multimodal RAG</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>
    <div class="meta">OpenCLIP · ChromaDB · ReAct Agents · GPT-4o</div>

    <ul>
      <li>Architected a production-style multimodal RAG system combining shared embedding space alignment with hybrid retrieval and agent-based reasoning.</li>
      <li>Indexed 8K+ multimodal documents using CUDA-accelerated embedding pipelines.</li>
      <li>Designed hybrid reranking (cosine similarity + lexical overlap) to improve grounding robustness.</li>
      <li>Implemented ReAct tool-calling loop for evidence-first reasoning and controlled refusal behavior.</li>
      <li>Built quantitative evaluation framework for retrieval and generation reliability.</li>
    </ul>

    <div class="metrics">
      <div class="metric"><strong>Recall@5</strong><br>84.5%</div>
      <div class="metric"><strong>MRR</strong><br>0.81</div>
      <div class="metric"><strong>Faithfulness</strong><br>9.06 / 10</div>
      <div class="metric"><strong>Refusal Rate</strong><br>3.3%</div>
    </div>

    <a href="https://github.com/abc/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git" class="button">
      View Full Repository
    </a>

    <div style="margin-top:40px;">
      <h3>System Architecture</h3>
      <img src="assets/rag_architecture.png" style="width:100%; border-radius:12px; border:1px solid rgba(255,255,255,.1);">
    </div>
  </div>
</div>

<!-- OTHER PROJECTS -->
<div class="section">
  <h2 class="accent">Selected Projects</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Deep Learning-Based Predictive Maintenance</h3>
    <div class="meta">Industry Collaboration · 100K+ Vibration Signals</div>
    <ul>
      <li>Engineered triaxial vibration data pipeline for rotating machinery fault detection.</li>
      <li>Built dual-encoder CNN combining time-domain and FFT frequency representations.</li>
      <li>Applied contrastive self-supervised learning achieving 91% classification accuracy.</li>
    </ul>
  </div>

  <div class="card">
    <h3>LLM-Powered Wikipedia RAG Assistant</h3>
    <ul>
      <li>Built retrieval-augmented conversational assistant with grounded answer generation.</li>
      <li>Integrated semantic search, vector indexing, and tool-based reasoning safeguards.</li>
    </ul>
  </div>

  <div class="card">
    <h3>MIT Indoor Scene Classification</h3>
    <ul>
      <li>Implemented DenseNet-like teacher model with SE attention blocks.</li>
      <li>Applied knowledge distillation and ensemble voting achieving 76% F1-score.</li>
    </ul>
  </div>

  <div class="card">
    <h3>Reinforcement Learning for Smart Energy Systems</h3>
    <ul>
      <li>Implemented PPO and SAC agents in CityLearn environment.</li>
      <li>SAC achieved best performance on energy efficiency and peak load reduction.</li>
    </ul>
  </div>
</div>

<!-- CONTACT -->
<div class="contact">
  <h3>Contact</h3>
  <p>
    Email: sarayusd31@gmail.com &nbsp;&nbsp;|&nbsp;&nbsp;
    GitHub: <a href="https://github.com/sarayusd">https://github.com/sarayusd</a> &nbsp;&nbsp;|&nbsp;&nbsp;
    LinkedIn: <a href="https://www.linkedin.com/in/sarayusd/">https://www.linkedin.com/in/sarayusd/</a>
  </p>
</div>

</div>





