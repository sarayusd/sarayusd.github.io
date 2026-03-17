---
layout: default
title: Sarayu Sivakumar Dhaya
---
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

/* ============================= */
/* COLOR SYSTEM — PURPLE + GOLD */
/* ============================= */
:root{
  --bg:#08060f;
  --panel:#121022;
  --panel-2:#0e0b18;
  --border:rgba(255,255,255,.08);

  --text:#f5f4fa;
  --muted:#b8b4cc;

  --accent:#c6a84f;   /* gold */
  --accent2:#7b3fe4;  /* purple */
}

/* ============================= */
/* GLOBAL RESET */
/* ============================= */
*{ box-sizing:border-box; }

html, body{
  margin:0;
  padding:0;
  font-family:'Inter',sans-serif;
  color:var(--text);

  background:
    radial-gradient(900px 400px at 70% 0%, rgba(123,63,228,.25), transparent 60%),
    radial-gradient(700px 300px at 20% 20%, rgba(198,168,79,.12), transparent 60%),
    linear-gradient(180deg,#120c1f 0%, #08060f 70%, #000000 100%);

  overflow-x:hidden;
}

/* Remove Cayman layout constraints */
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

/* ============================= */
/* HEADER */
/* ============================= */
.page-header{
  background: linear-gradient(
    135deg,
    #2a1244 0%,
    #3b1e5c 40%,
    #b8860b 75%,
    #000000 100%
  ) !important;

  padding:100px 20px 120px 20px !important;
  border-bottom:none !important;
}

.project-name{
  font-size:56px !important;
  font-weight:800 !important;
  color:#ffffff !important;
  letter-spacing:-1px;
}

.project-tagline{
  font-size:20px !important;
  color:rgba(255,255,255,0.85) !important;
}

/* ============================= */
/* LAYOUT */
/* ============================= */
.wrapper{
  width:min(1150px, calc(100vw - 80px));
  margin:0 auto;
  padding:80px 0;
}

.section{
  margin:120px 0;
}

/* ============================= */
/* UNIFIED SECTION HEADINGS */
/* ============================= */
.section-title,
.section h2{
  font-size:42px;
  font-weight:700;
  margin:0 0 20px 0;

  background: linear-gradient(90deg, var(--accent2), var(--accent));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  letter-spacing:-0.5px;
  text-shadow: 0 0 25px rgba(198,168,79,.15);
}

.section-title{
  text-transform:none;
}

/* Section underline */
.rule{
  width:80px;
  height:3px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  border-radius:999px;
  margin:20px 0 35px 0;
}

/* ============================= */
/* TEXT */
/* ============================= */
p{
  font-size:19px;
  line-height:1.9;
  color:var(--muted);
  margin-bottom:22px;
}

ul{
  padding-left:24px;
  margin-top:14px;
}

li{
  margin-bottom:14px;
  font-size:18px;
  line-height:1.8;
  color:var(--muted);
}

/* ============================= */
/* CARD LAYOUT */
/* ============================= */
.card{
  background:linear-gradient(180deg,var(--panel),var(--panel-2));
  border:1px solid rgba(198,168,79,.15);
  border-radius:18px;
  padding:45px;
  margin-bottom:40px;
  box-shadow:0 20px 60px rgba(0,0,0,.55);
  transition: all .25s ease;
}

.card:hover{
  transform:translateY(-4px);
  border-color:rgba(198,168,79,.35);
}

/* ===== Card Header Layout ===== */
.card-header{
  display:flex;
  justify-content:space-between;
  align-items:flex-start;
  gap:20px;
  margin-bottom:6px;
}

.card-header h3{
  margin:0;
  font-size:26px;
  font-weight:600;
  line-height:1.3;
  flex:1;
  color:#ffffff;
}

/* ===== Repo Link ===== */
.repo-link{
  font-size:14px;
  font-weight:600;
  color:var(--accent);
  text-decoration:none;
  white-space:nowrap;
  margin-top:6px;
  transition:.25s ease;
}

.repo-link:hover{
  color:var(--accent2);
}

/* ===== Project Stack (Skills line) ===== */
.project-stack{
  font-size:14px;
  font-weight:500;
  margin-bottom:20px;
  margin-top:8px;
  color:#d4b35a;
  letter-spacing:.4px;
  padding-bottom:6px;
  border-bottom:1px solid rgba(198,168,79,.15);
}

/* Meta */
.meta{
  font-size:15px;
  color:rgba(255,255,255,.5);
  margin-bottom:14px;
}

/* ============================= */
/* RESULT + ARCH BOXES */
/* ============================= */
.results-box{
  background:rgba(198,168,79,.05);
  border:1px solid rgba(198,168,79,.2);
  padding:20px;
  border-radius:12px;
  margin-top:25px;
}

.arch-box{
  background:#ffffff;
  padding:30px;
  border-radius:16px;
  margin-top:30px;
  box-shadow:0 20px 60px rgba(0,0,0,.55);
}

.demo-box{
  background:#ffffff;
  padding:30px;
  border-radius:16px;
  margin-top:40px;
  box-shadow:0 20px 60px rgba(0,0,0,.55);
  text-align:center;
}

/* ============================= */
/* LINKS */
/* ============================= */
a{
  color:var(--accent);
  text-decoration:none;
  transition:.2s ease;
}

a:hover{
  color:var(--accent2);
}

/* ============================= */
/* CONTACT */
/* ============================= */
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

/* ============================= */
/* RESPONSIVE */
/* ============================= */
@media(max-width:900px){
  .wrapper{ width:calc(100vw - 40px); }
  .section-title,
  .section h2{
    font-size:30px;
  }
  .project-name{ font-size:40px !important; }
}
</style>

<div class="wrapper">

<!-- ABOUT ME -->
<div class="section">
  
  <div class="section-title">About Me</div>
  <div class="rule"></div>

  <p>
    I am a Master’s graduate in Artificial Intelligence from the University at Buffalo with 5+ years of professional software engineering experience building scalable backend systems and distributed architectures. My industry background shaped how I design AI systems prioritizing robustness, performance, and production readiness.
  </p>

  <p>
    I have built industry-collaborative predictive maintenance systems, multimodal Retrieval-Augmented Generation (RAG) architectures, hybrid semantic + lexical retrieval engines, reinforcement learning agents, and deep CNN models with knowledge distillation.
  </p>

  <p>
    My focus lies in building measurable, grounded, and scalable AI systems particularly in Generative AI, multimodal retrieval, deep learning, and agent-based reasoning frameworks.
  </p>
</div>

<!-- PROJECTS -->
<div class="section">
  <div class="section-title">Project Experience</div>
  <div class="rule"></div>

  <!-- PREDICTIVE MAINTENANCE -->
  <div class="card">

    <div class="card-header">
      <h3>Deep Learning-Based Predictive Maintenance of Rotating Machinery</h3>
    </div>

    <div class="project-stack">
      PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention
    </div>

    <div class="meta">University – Industry Collaboration (Machinery Monitoring Systems LLC)</div>

    <ul>
      <li>Engineered a triaxial vibration acquisition pipeline on a custom rotor test rig, generating 100K+ vibration signals across multiple fault conditions.</li>
      <li>Developed a dual-encoder 1D CNN combining time-domain waveforms with FFT-based frequency representations using channel-wise attention.</li>
      <li>Implemented multi-window signal segmentation to capture progressive fault behavior and reduce transient noise sensitivity.</li>
      <li>Applied contrastive self-supervised pretraining achieving <strong>91% downstream classification accuracy</strong> with reduced labeled data dependence.</li>
    </ul>

    <div class="arch-box">
      <strong style="color:#111;">System Architecture</strong>
      <img src="{{ '/images/mmsp.png' | relative_url }}"
           style="width:100%; margin-top:20px; border-radius:12px;">
    </div>

  </div>


  <!-- RAG PROJECT -->
<div class="card">

  <div class="card-header">
    <h3>Multimodal Scene Retrieval System with Hybrid Search and RAG</h3>
    <a class="repo-link" href="https://github.com/sarayusd/Multimodal-Scene-Retrieval-System-with-Hybrid-Search-and-RAG.git">
      Source Code →
    </a>
  </div>

<div class="project-stack">
  OpenCLIP · LangChain · ChromaDB · BM25 · SentenceTransformers · GPT-4o · PyTorch
</div>
<div style="text-align:center; margin: 20px 0;">
  <a href="{{ '/images/test.mp4' | relative_url }}" target="_blank"
     style="text-decoration:none; font-size:18px;">
    ▶️ Watch Demo
  </a>
</div>
<ul>
  <li>Built a multimodal retrieval system supporting text→image, image→image, and image→caption search using OpenCLIP embeddings on the COCO captions dataset.</li>

  <li>Implemented a multi-stage retrieval pipeline combining dense CLIP vector search, BM25 lexical hybrid retrieval, and SentenceTransformers cross-encoder reranking.</li>

  <li>Indexed image and caption embeddings in ChromaDB and implemented a fallback retrieval cascade (reranked → hybrid → dense → BM25) for robust query handling.</li>

  <li>Added an LLM-based verification step where GPT-4o audits retrieved images against the query before explanation generation.</li>

  <li>Developed a LangChain few-shot RAG prompting pipeline that formats retrieved captions as evidence to generate grounded scene explanations using GPT-4o-mini.</li>

  <li>Built an evaluation framework measuring retrieval performance using Recall@1, Recall@5, Precision@5, MRR, nDCG, and latency.</li>
</ul>

<div class="arch-box" style="text-align:center;">
  <strong style="color:#111;">System Architecture</strong>

  <img src="{{ '/images/agent.png' | relative_url }}"
       style="width:50%; max-width:500px; margin-top:20px; border-radius:12px;">
</div>

</div>

  <!-- WIKIPEDIA RAG -->
  <div class="card">

    <div class="card-header">
      <h3>LLM-Powered RAG Conversational Assistant (Wikipedia)</h3>
      <a class="repo-link" href="https://github.com/sarayusd/LLM-powered-Chatbot-with-RAG-using-LlamaIndex.git">
        Source Code →
      </a>
    </div>

    <div class="project-stack">
      RAG · Semantic Search · Vector Embeddings · Grounded Generation
    </div>

    <ul>
      <li>Built a conversational assistant using Retrieval-Augmented Generation over Wikipedia corpus.</li>
      <li>Integrated semantic vector search and grounded prompting to reduce hallucination risk.</li>
      <li>Implemented context-aware answer generation with evidence traceability.</li>
    </ul>

  </div>

  <div class="card">

  <div class="card-header">
    <h3>LinkedIn Job Market Analysis - Big Data Pipeline</h3>
    <a class="repo-link" href="https://github.com/sarayusd/Job-Market-Analysis-.git">
      Source Code →
    </a>
  </div>

  <div class="project-stack">
    PySpark · Hadoop (HDFS) · Spark MLlib · Python · Docker · Data Analysis
  </div>

  <ul>
    <li>Built an end-to-end big data pipeline to process ~1.3M LinkedIn job postings using Hadoop (HDFS) and PySpark, including cluster setup and data ingestion.</li>
    <li>Performed large-scale data cleaning and preprocessing, handling missing values, standardizing job titles/locations, and structuring unstructured skill data.</li>
    <li>Conducted EDA and feature engineering (TF-IDF, skill extraction) to analyze job trends, in-demand skills, and company hiring patterns.</li>
    <li>Developed ML models for classification, regression, and clustering using Spark MLlib and evaluated performance using standard metrics.</li>
  </ul>

</div>
  <!-- MIT SCENE RECOGNITION -->
  <div class="card">

    <div class="card-header">
      <h3>Scene Recognition with Deep CNNs (MIT Indoor67)</h3>
      <a class="repo-link" href="https://github.com/sarayusd/Scene-Recognition-with-Deep-CNNs.git">
        Source Code →
      </a>
    </div>

    <div class="project-stack">
      PyTorch · CNN · SE Blocks · Knowledge Distillation · Ensemble Learning
    </div>

    <ul>
      <li>Implemented DenseNet-like teacher architecture with SE attention blocks.</li>
      <li>Applied knowledge distillation to train compact student model.</li>
      <li>Ensembled teacher + distilled models achieving <strong>76% F1-score</strong>.</li>
    </ul>

  </div>


  <!-- CITYLEARN RL -->
  <div class="card">

    <div class="card-header">
      <h3>Sustainable Energy Management in Smart Homes (CityLearn RL)</h3>
      <a class="repo-link" href="https://github.com/sarayusd/Sustainable-Energy-Management-with-Reinforcement-Learning.git">
        Source Code →
      </a>
    </div>

    <div class="project-stack">
      Reinforcement Learning · PPO · SAC · Energy Optimization
    </div>

    <ul>
      <li>Implemented PPO and SAC reinforcement learning agents in CityLearn environment.</li>
      <li>Designed reward functions balancing energy cost, carbon emissions, and peak demand.</li>
      <li>SAC achieved highest efficiency and lowest peak demand across experiments.</li>
    </ul>

  </div>

</div>
<!-- INDUSTRY -->
<!-- INDUSTRY -->
<div class="section">
  <div class="section-title"></div>
  <h2 class="accent">Professional Experience</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Tata Consultancy Services | IT Analyst</h3>
    <div class="meta">2018 – 2019</div>

    <ul>
      <li>Developed and maintained high-volume Java backend systems supporting mission-critical financial trade and settlement workflows.</li>
      <li>Designed optimized SQL stored procedures and query pipelines, improving execution efficiency and reducing latency in production environments.</li>
      <li>Collaborated within Agile teams to deliver scalable distributed services with strong emphasis on reliability and fault tolerance.</li>
      <li>Performed production debugging, log analysis, and performance tuning across multi-tier enterprise systems.</li>
    </ul>
  </div>

  <div class="card">
    <h3>Capgemini | Associate Consultant</h3>
    <div class="meta">2013 – 2018</div>

    <ul>
      <li>Designed and implemented RESTful Java microservices powering enterprise dashboards and operational reporting systems.</li>
      <li>Built modular backend components enabling secure API integrations and structured data pipelines.</li>
      <li>Resolved distributed system bottlenecks through performance profiling and code optimization.</li>
      <li>Provided production support across large-scale client systems ensuring uptime, stability, and SLA compliance.</li>
    </ul>
  </div>
</div>

<!-- CONTACT -->
<div class="contact">
<h3>Contact</h3>
<p>
Email: <a href="mailto:sarayusd31@gmail.com">sarayusd31@gmail.com</a> |
GitHub: <a href="https://github.com/sarayusd">github.com/sarayusd</a> |
LinkedIn: <a href="https://linkedin.com/in/sarayusd">linkedin.com/in/sarayusd</a>
</p>
</div>

</div>
