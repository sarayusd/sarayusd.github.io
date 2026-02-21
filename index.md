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

h1{
  font-size:56px;
  font-weight:800;
  margin:0 0 15px 0;
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
  margin-top:30px;
}

.demo-box{
  margin-top:35px;
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
  h1{ font-size:40px; }
  h2{ font-size:30px; }
}
</style>

<div class="wrapper">

<!-- SUMMARY -->
<div class="section">
  <div class="section-title">Summary</div>
  <h2 class="accent">Applied AI · Deep Learning · LLM Systems</h2>
  <div class="rule"></div>

  <p>
  I am a Master’s graduate in Artificial Intelligence with 5+ years of backend engineering experience across distributed systems. I design production-style AI systems combining multimodal embeddings, hybrid retrieval pipelines, agent-based reasoning, and measurable evaluation for reliable deployment.
  </p>
</div>

<!-- PROJECTS -->
<!-- PROJECTS -->
<div class="section">
  <div class="section-title">Project Experience</div>
  <div class="rule"></div>

  <!-- PREDICTIVE MAINTENANCE (Moved to Top) -->
  <div class="card">
    <h3>Deep Learning-Based Predictive Maintenance of Rotating Machinery</h3>
    <div class="meta">University – Industry Collaboration (Machinery Monitoring Systems LLC)</div>
   
    <ul>
      <li>Engineered a triaxial vibration acquisition pipeline on a custom rotor test rig, generating 100K+ vibration signals across multiple fault conditions.</li>
      <li>Developed a dual-encoder 1D CNN combining time-domain waveforms with FFT-based frequency representations using channel-wise attention.</li>
      <li>Implemented multi-window signal segmentation to capture progressive fault behavior and reduce transient noise sensitivity.</li>
      <li>Applied contrastive self-supervised pretraining achieving <strong>91% downstream classification accuracy</strong> with reduced labeled data dependence.</li>
    </ul>

    <div class="arch-box" style="
    background:#ffffff;
    padding:30px;
    border-radius:16px;
    margin-top:30px;
    box-shadow:0 20px 60px rgba(0,0,0,.35);
      ">
  
    <strong style="color:#111;">System Architecture</strong>
  
    <img src="{{ '/images/mmsp.png' | relative_url }}"
         style="width:100%; margin-top:20px; border-radius:12px;">
    </div>

    <div class="tags">
      PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention
    </div>
  </div>


  <!-- RAG PROJECT -->
  <div class="card">
    <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>
     <div class="arch-box">
      
    <div class="smalllink">
      <a href="https://github.com/sarayusd/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git">
        View Source Code
      </a>
    </div>

    <ul>
      <li>Architected a production-style multimodal RAG system using OpenCLIP shared embedding space, ChromaDB vector search, hybrid semantic + lexical reranking, and ReAct-based tool reasoning.</li>
      <li>Indexed 8K+ multimodal image-text pairs using CUDA-accelerated embedding pipelines.</li>
      <li>Designed hybrid ranking pipeline (cosine similarity + keyword overlap) to reduce semantic drift and improve grounding robustness.</li>
      <li>Implemented agentic tool-calling loop enabling evidence-first reasoning and controlled refusal behavior.</li>
      <li>Built a quantitative evaluation framework measuring retrieval accuracy and LLM grounding reliability.</li>
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

    <div class="arch-box" style="
    background:#ffffff;
    padding:30px;
    border-radius:16px;
    margin-top:30px;
    box-shadow:0 20px 60px rgba(0,0,0,.35);
      ">
  
    <strong style="color:#111;">System Architecture</strong>
  
    <img src="{{ '/images/ragAgent.png' | relative_url }}"
         style="width:100%; margin-top:20px; border-radius:12px;">
    </div>

    
    <div class="demo-box" style="margin-top:30px; text-align:center;">
      <strong>System Demo</strong>
    
      <video controls
             style="width:65%;
                    max-width:700px;
                    margin-top:15px;
                    border-radius:12px;
                    border:1px solid rgba(255,255,255,.15);
                    box-shadow:0 15px 40px rgba(0,0,0,.35);">
    
        <source src="{{ '/images/rag.mp4' | relative_url }}" type="video/mp4">
    
        Your browser does not support the video tag.
      </video>
    </div>

    <div class="tags">
      OpenCLIP · LangChain · ChromaDB · Hybrid Retrieval · ReAct Agents · GPT-4o · CUDA
    </div>
  </div>


  <!-- WIKIPEDIA RAG -->
  <div class="card">
    <h3>LLM-Powered RAG Conversational Assistant (Wikipedia)</h3>
    <div class="smalllink">
      <a href="https://github.com/sarayusd/LLM-powered-Chatbot-with-RAG-using-LlamaIndex.git">
        View Source Code
      </a>
    </div>
    <ul>
      <li>Built a conversational assistant using Retrieval-Augmented Generation over Wikipedia corpus.</li>
      <li>Integrated semantic vector search and grounded prompting to reduce hallucination risk.</li>
      <li>Implemented context-aware answer generation with evidence traceability.</li>
    </ul>
    <div class="tags">RAG · Semantic Search · Vector Embeddings · Grounded Generation</div>
  </div>


  <!-- MIT SCENE RECOGNITION -->
  <div class="card">
    <h3>Scene Recognition with Deep CNNs (MIT Indoor67)</h3>
    <div class="smalllink">
      <a href="https://github.com/sarayusd/Scene-Recognition-with-Deep-CNNs.git">
        View Source Code
      </a>
    </div>
    <ul>
      <li>Implemented DenseNet-like teacher architecture with SE attention blocks.</li>
      <li>Applied knowledge distillation to train compact student model.</li>
      <li>Ensembled teacher + distilled models achieving <strong>76% F1-score</strong>.</li>
    </ul>
    <div class="tags">PyTorch · CNN · SE Blocks · Knowledge Distillation · Ensemble Learning</div>
  </div>


  <!-- CITYLEARN RL -->
  <div class="card">
    <h3>Sustainable Energy Management in Smart Homes (CityLearn RL)</h3>
    <div class="smalllink">
      <a href="https://github.com/sarayusd/Sustainable-Energy-Management-with-Reinforcement-Learning.git">
        View Source Code
      </a>
    </div>
    <ul>
      <li>Implemented PPO and SAC reinforcement learning agents in CityLearn environment.</li>
      <li>Designed reward functions balancing energy cost, carbon emissions, and peak demand.</li>
      <li>SAC achieved highest efficiency and lowest peak demand across experiments.</li>
    </ul>
    <div class="tags">Reinforcement Learning · PPO · SAC · Energy Optimization</div>
  </div>

</div>

<!-- INDUSTRY -->
<div class="section">
  <div class="section-title">Industry Background</div>
  <h2 class="accent">Software Engineering Experience</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Tata Consultancy Services | IT Analyst</h3>
    <div class="meta">2018 – 2019</div>
    <ul>
      <li>Developed and maintained high-volume Java backend systems for financial trade workflows.</li>
      <li>Optimized SQL procedures improving system performance and production reliability.</li>
      <li>Delivered production-grade systems within Agile environments.</li>
    </ul>
  </div>

  <div class="card">
    <h3>Capgemini | Associate Consultant</h3>
    <div class="meta">2013 – 2018</div>
    <ul>
      <li>Designed RESTful Java microservices for enterprise dashboards.</li>
      <li>Resolved distributed system performance bottlenecks and integration issues.</li>
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






