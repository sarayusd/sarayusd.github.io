---
layout: default
title: Sarayu Sivakumar Dhaya
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#070b18;
  --panel:#111a2f;
  --border:rgba(255,255,255,.10);
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
    radial-gradient(1200px 600px at 20% 10%, rgba(56,189,248,.20), transparent 60%),
    radial-gradient(1000px 600px at 80% 20%, rgba(34,197,94,.15), transparent 60%),
    linear-gradient(180deg,#060913 0%,#070b18 100%);
  overflow-x:hidden;
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

footer,
.site-footer,
.page-footer{
  display:none !important;
}

.wrapper{
  width:min(1150px, calc(100vw - 80px));
  margin:0 auto;
  padding:80px 0;
}

.section{
  margin:120px 0;
}

.section-title{
  font-size:14px;
  letter-spacing:.2em;
  text-transform:uppercase;
  color:rgba(255,255,255,.6);
  margin-bottom:10px;
}

h2{
  font-size:42px;
  font-weight:700;
  margin:0 0 20px 0;
}

.accent{ color:var(--accent); }

.rule{
  width:80px;
  height:3px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  border-radius:999px;
  margin:20px 0 35px 0;
}

p{
  font-size:19px;
  line-height:1.9;
  color:var(--muted);
  margin-bottom:22px;
}

.card{
  background:linear-gradient(180deg,rgba(17,26,47,.95),rgba(15,23,42,.9));
  border:1px solid var(--border);
  border-radius:18px;
  padding:45px;
  margin-bottom:40px;
  box-shadow:0 20px 60px rgba(0,0,0,.35);
}

.card h3{
  font-size:24px;
  margin:0 0 8px 0;
}

.meta{
  font-size:15px;
  color:rgba(255,255,255,.6);
  margin-bottom:14px;
}

.smalllink{
  font-size:15px;
  margin:0 0 16px 0;
}

ul{
  padding-left:24px;
  margin-top:15px;
}

li{
  margin-bottom:14px;
  font-size:18px;
  line-height:1.8;
  color:var(--muted);
}

.results-box{
  background:rgba(255,255,255,.04);
  border:1px solid rgba(255,255,255,.1);
  padding:20px;
  border-radius:12px;
  margin-top:25px;
}

.arch-box{
  background:#ffffff;
  padding:30px;
  border-radius:16px;
  margin-top:30px;
  box-shadow:0 20px 60px rgba(0,0,0,.35);
}

.demo-box{
  background:#ffffff;
  padding:30px;
  border-radius:16px;
  margin-top:40px;
  box-shadow:0 20px 60px rgba(0,0,0,.35);
  text-align:center;
}

.tags{
  margin-top:20px;
  font-size:15px;
  color:rgba(255,255,255,.6);
}

.contact{
  text-align:center;
  margin-top:120px;
  padding-bottom:40px;
}

.contact h3{
  font-size:28px;
  margin-bottom:18px;
}

.contact p{
  font-size:18px;
  color:var(--muted);
  margin:0;
}

a{
  color:var(--accent2);
  text-decoration:none;
}
a:hover{ text-decoration:underline; }

@media(max-width:900px){
  .wrapper{ width:calc(100vw - 40px); }
  h2{ font-size:30px; }
}
</style>

<div class="wrapper">

<!-- SUMMARY -->
<div class="section">
    <h2 class="accent">AI Engineer · Deep Learning · Agentic Systems</h2>
  <div class="section-title">About Me</div>

  <div class="rule"></div>

  <div class="summary-grid">
    <div>
      <p>
        I am a Master’s graduate in Artificial Intelligence from the University at Buffalo with 5+ years of professional software engineering experience building scalable backend systems and distributed architectures. My industry foundation shapes how I design AI systems prioritizing robustness, performance, and production readiness.
      </p>

      <p>
        During my graduate studies, I partnered with Machinery Monitoring Systems LLC on a real-world predictive maintenance initiative involving triaxial vibration acquisition, hardware-level experimentation, and iterative deep learning refinement under operational constraints.
      </p>

      <p>
        I have architected LLM-powered systems including Retrieval-Augmented Generation (RAG) assistants and agentic multimodal retrieval pipelines integrating shared embedding spaces, hybrid reranking, and evidence-first reasoning workflows.
      </p>

      <p>
        My focus lies in building practical deep learning and LLM-based systems particularly in Generative AI, multimodal RAG, and agent architectures engineered for measurable performance and reliable real-world deployment.
      </p>
    </div>
  </div>
</div>

<!-- PROJECTS -->
<div class="section">
  <div class="section-title">Project Experience</div>
  <div class="rule"></div>

  <!-- Predictive Maintenance -->
  <div class="card">
    <h3>Deep Learning-Based Predictive Maintenance of Rotating Machinery</h3>
    <div class="meta">University – Industry Collaboration (Machinery Monitoring Systems LLC)</div>

    <ul>
      <li>Engineered a triaxial vibration acquisition pipeline generating 100K+ signals across multiple fault conditions.</li>
      <li>Developed dual-encoder 1D CNN combining time-domain + FFT features with channel-wise attention.</li>
      <li>Applied contrastive self-supervised learning achieving <strong>91% classification accuracy</strong>.</li>
    </ul>

    <div class="arch-box">
      <strong style="color:#111;">System Architecture</strong>
      <img src="{{ '/images/mmsp.png' | relative_url }}"
           style="width:100%; margin-top:20px; border-radius:12px;">
    </div>

    <div class="tags">
      PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention
    </div>
  </div>

  <!-- RAG -->
  <div class="card">
    <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>

    <div class="smalllink">
      <a href="https://github.com/sarayusd/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git">
        View Source Code
      </a>
    </div>

    <ul>
      <li>Architected multimodal RAG using OpenCLIP embeddings, ChromaDB vector search, hybrid reranking, and ReAct reasoning loop.</li>
      <li>Indexed 8K+ image-text pairs with CUDA-accelerated embedding pipelines.</li>
      <li>Built evaluation framework measuring retrieval and LLM grounding reliability.</li>
    </ul>

    <div class="results-box">
      <strong>Results</strong>
      <ul>
        <li><strong>Recall@5:</strong> 84.5%</li>
        <li><strong>MRR:</strong> 0.81</li>
        <li><strong>Faithfulness:</strong> 9.06 / 10</li>
        <li><strong>Refusal Rate:</strong> 3.3%</li>
      </ul>
    </div>

    <div class="arch-box">
      <strong style="color:#111;">System Architecture</strong>
      <img src="{{ '/images/argAgent.png' | relative_url }}"
           style="width:100%; margin-top:20px; border-radius:12px;">
    </div>

    <div class="demo-box">
      <strong style="color:#111;">System Demo</strong>
      <video controls style="width:70%; max-width:800px; margin-top:20px; border-radius:12px;">
        <source src="{{ '/images/rag.mp4' | relative_url }}" type="video/mp4">
      </video>
    </div>

    <div class="tags">
      OpenCLIP · LangChain · ChromaDB · Hybrid Retrieval · ReAct Agents · GPT-4o · CUDA
    </div>
  </div>

</div>

<!-- CONTACT -->
<div class="contact">
  <h3>Contact</h3>
  <p>
    Email: <a href="mailto:sarayusd31@gmail.com">sarayusd31@gmail.com</a> |
    GitHub: <a href="https://github.com/sarayusd">github.com/sarayus</a> |
    LinkedIn: <a href="https://linkedin.com/in/sarayusd">linkedin.com/in/sarayusd</a>
  </p>
</div>

</div>
